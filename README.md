# Project-1-Group
Group members: Tavis Goldwire

  The code in GBIF Project satisfies the requirements for Project 1 by drawing from the Global Biodiversity Information Facility API located at https://techdocs.gbif.org/en/openapi/. The code allows user input of a species scientific name. It then displays 5 pieces of information: Scientific name, common names, IUCN status, distribution, and finally a description. For the purposes of space I have attempted to limit the description. It saves all these results in a json file.

  The code utilizes a continous while loop that allows a user to submit multiple species for data retreival. To break the loop a user must submit 'x'. The code should work for all species that the API has information for. Certain species such as _Canis lupus _ cause a bit of diffiuclty in the API due to Canis lupis familiaris, the dog, sharing information with it. The dog and grey wolf have much differnet lifestyles, distributions, etc. that the API does not account for. 

  
