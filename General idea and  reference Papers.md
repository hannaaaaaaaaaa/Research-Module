
### Proposal 

- **Research question**: What is the lasting impact of extractive institutions and through what mechanisms do they work?
- **Idea**: Better understanding how participation in the slave cycles impacts modern day outcomes in Brazilian municipalities through an IV approach 
	- **OLS Approach**: The quantity of slaves in the population in 1872 (See under) as the variable representing the intensity of the slavery cycle in each city, with the current day outcomes being measured by GDP, education levels and other key variables.
	- **Endogeneity problem**: Slavery measurements are correlated with many other variables that can possibly influence modern day outcomes such as GDP and institutional quality, such as city's historical development or discrimination (Acemoglu Robinson Johnson 2001)
	- **Solution**: Employ either concentration of *Quilombos* (see explanation below-Preferred) or percentage of blacks in the population nowadays [(Nakabashi and Pereira (2023](https://ideas.repec.org/p/anp/en2013/090.html))
		- **Relevance**: Quilombos were formed by runaway slaves, so there is a clear relationship with the slave percentage variable;
		- **Exogeneity**: There is no correlation between economic activity and *Quilombo* formation, excluding through the quantity of slaves in the population (Relevance). *Quilombos* formation was not dependent on economic factors, or other relevant municipality characteristic 
- **Data**: 
	- Municipality data from [IBGE](https://www.ibge.gov.br/en/geosciences/territorial-organization/territorial-meshes/18890-municipal-mesh.html) (including share of slaves by city)
	- *Quilombo* intensity by municipality  [Fundacao Cultural Palmares](https://www.gov.br/palmares/pt-br/departamentos/protecao-preservacao-e-articulacao/certificacao-quilombola)
	- Other control data like geographical conditions or distance to Portugal (???)

### Reference Papers


- **Paper 1**:  [Institutional Development and Colonial Heritage within Brazil](https://www.cambridge.org/core/journals/journal-of-economic-history/article/institutional-development-and-colonial-heritage-within-brazil/A96BB58C0D71CA42E4FE9E1D1C70010A) 
	- The determinants of local institutions in Brazil; Shows that institutional quality and distribution of land are partly inherited from the colonial histories
	- Studies the impact of sugar cane and gold boom participation in municipality inst. quality
	- **Data**: Participation in each boom, distance to portugal, 
		- Institutional measures: Brazilian Agricultural Gini Coefficient - 1996 ; Index of governance practices (IBGE) - 1997 to 2000; Access to justice index (IBGE) - 2001
	- **Empirical Estimation**: 
		- ![[Pasted image 20241011153320.png]]
		- _Zi_ is the measure of _governance_, _access to justice, land Gini_, or the public good characteristic. _Si_ is the sugar cane boom variable, _Gi_ is the gold boom variable, _Pi_ is distance to Portugal, _Xi_ is a vector of geographic attributes (_distance to equator, distance to coast, rainfall, sunshine, altitude, temperature, and soils_, defined in the Appendix)
		- Two interaction terms: Sugar cane boom and portugal dist, and Gold and portugal dist
	- Data Avaliability: Upon request
///


- **Paper 2**: [Slaves migrants and Development in Brazil 1872-1923]
	- Illustrates the adverse impact of slavery on a broad range of indicators of economic development, both while slavery still existed and more than 30 years after its abolition
	- Uses *quilombos* (community of runaway slaves) concentration to measure instensity of slavery experience in three states: Minas Gerais, Sao Paulo and Rio de Janeiro 
	- **Data**: the incidence of slaves in the total population in 1872 (Census 1872); presence and number of *Quilombos* present in each municipality (Fundacao Cultural Palmares)
		- Three measures of the intensity of slavery:
		1. the share of slaves in the total population from the 1872 census before abolishment of slavery in **1888** (SlaveShare), 
		2. a dummy indicating the presence of a *Quilombo* community in a municipality (QuilTreat), 
		3. a variable containing the number of *Quilombos* in a municipality (QuilNumb) 
	- **Empirical Strategy**: Selection on Observables 
	- **Data Avaliability**: Upon request

