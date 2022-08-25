# Core United Nations Human Rights Instruments: Their Ratification Status

This repository contains data on the ratification of the core United Nations human rights instruments. The data was extrapolated from the United Nations Treaty Collection's [webpage](https://treaties.un.org/Pages/ViewDetails.aspx?src=TREATY&mtdsg_no=IV-2&chapter=4&clang=_en). 

**NOTE**: *These files does not include all state parties to the convention. They only measure UN member states' willingness to ratify these legal instruments*. 

## Legal Instruments:

- **ICERD**: *International Convention on the Elimination of All Forms of Racial Discrimination* (1965)
- **ICCPR**: *International Covenant on Civil and Political Rights* (1966)
- **ICESCR**: *International Covenant on Economic, Social and Cultural Rights* (1966)
- **CEDAW**: *Convention on the Elimination of All Forms of Discrimination against Women* (1979)
- **CAT**: *Convention against Torture and Other Cruel, Inhuman or Degrading Treatment or Punishment* (1984)
- **CRC**: *Convention on the Rights of the Child* (1989)
- **ICMW**: *International Convention on the Protection of the Rights of All Migrant Workers and Members of Their Families* (1990)
- **CPED**: *International Convention for the Protection of All Persons from Enforced Disappearance* (2006)
- **CRPD**: *Convention on the Rights of Persons with Disabilities* (2006)
- **ICESCR-OP**: *Optional Protocol to the Covenant on Economic, Social and Cultural Rights* (2008)
- **ICCPR-OP1**: *Optional Protocol to the International Covenant on Civil and Political Rights* (1966)
- **ICCPR-OP2**: *Second Optional Protocol to the International Covenant on Civil and Political Rights, Aiming at the Abolition of the Death Penalty* (1989)
- **OP-CEDAW**: *Optional Protocol to the Convention on the Elimination of All Forms of Discrimination against Women* (1999)
- **OP-CRC-AC**: *Optional Protocol to the Convention on the Rights of the Child on the Involvement of Children in Armed Conflict* (2000)
- **OC-CRC-SC**: *Optional Protocol to the Convention on the Rights of the Child on the Sale of Children, Child Prostitution and Child Pornography* (2000)
- **OP-CRC-IC**: *Optional Protocol to the Convention on the Rights of the Child on a Communications Procedure* (2011)
- **OP-CAT**: *Optional Protocol to the Convention against Torture and other Cruel, Inhuman or Degrading Treatment or Punishment* (2002)
- **OP-CRPD**: *Optional Protocol to the Convention on the Rights of Persons with Disabilities* (2006)

## Variables:

All the files use the same data structure:

- **iso2** - Represents the ISO2 code for the U.N. member state.
- **member** - The name of the UN member state, usually in the English language.
- **state party** - It is a dichotomous variable: 1 equals the member's ratification of the treaty.
- **year ratification or accession** - This is the year the member state ratified the the convention.
- **signatory** - A dichotomous variable that captures whether a state that has not ratified the treaty has signed it.
- **no action** - A dichotomous variable: 1 equals a state which has not signed or ratified the convention.
- **status** - The variable captures describes UN member state's status regarding the convention. It offers three options: state party, signatory state or no action.
- **notes** - Text explaining a particular observation.
 
