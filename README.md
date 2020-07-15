# directreducediron
Contains code for thermodynamic calculations for direct reduced iron using hydrogen. 
Some of the important assumptions made for the model are listed below :

All calculations are done for the production of 1 ton of liquid steel from the system.
5% impurities are present in the raw materials. The assumption is consistent with the plant data available in the literature.Primary components of the impurities are silica and alumina.
The iron ore pellets are heated from ambient temperature to 800 C,through an electrical heater of efficiency,  ηthermal=0.85ηthermal=0.85 .
Output from the shaft furnace would be metallic Fe and FeO. Remaining FeO will be reduced to pure iron in the electric arc furnace. Although, in practice some amount of FeO does not get reduced and becomes a part of the EAF slag.
The flow rate of hydrogen is considered to be higher than the stoichiometric requirements.
Apparent activation energy of 35 kJ/mol has been considered in the model.
Hydrogen produced from electrolysers are heated in an electrical heater with an efficiency of  ηthermal=0.6ηthermal=0.6 .

DRI stream exiting the shaft furnace is considered to be at a temperature of 800C.

The exhaust gas stream is assumed to be composed of hydrogen and water.The waste stream enthalpy varies with exhaust gas temperature and  λh2λh2 .
Energy required to separate hydrogen and water from the waste stream is not considered in the present calculations.
100\% DRI is fed into the furnace without any scrap. The quality of scrap has a significant effect on the energy consumption in a DRI.
Hot DRI is fed into the DRI at 700 \textdegree C as it saves considerable amount of electrical energy in the EAF.
Natural gas is not used for heating the material as its the general practice to use natural gas with scrap for initial heating.
As DRI is reduced only with Hydrogen, it is assumed that it does not contain any ferric carbide. Carbon required for reduction of remaining FeO in the EAF is supplied externally as coal or coke.
Temperature of the DRI being fed into the EAF is not taken into account into empirical energy models (Pfeifer2003). Thermodynamic modelling of the EAF has been done to get the specific energy consumption of the EAF with 100% DRI.
Carbon is added into the EAF to reduce the remaining FeO in the mix and also to generate CO for froth formation,which is essential for the operation of the EAF and to extend the life of the graphite electrodes and the refractory.
CaO and MgO are added in the EAF as slag formers to maintain the basicity of the EAF.The weight of CaO and MgO used are according to data published in the literature (Dilmac2015).
Efficiency parameters used in the EAF model for electrical and chemical energy are according to the reference
