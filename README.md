**Update! Alert! Attention!**  
We extended our work on Collective Scoping to **Collaborative Scoping** ([Github](https://github.com/leotraeg/CollaborativeScoping) or [Accepted Paper @EDBT26](https://www.openproceedings.org/2026/conf/edbt/paper-22.pdf)), a more scalable and robust schema linkability assessment method for heterogeneous schema matching scenarios.

# Scoping: Towards streamlined entity collections for multi-sourced Entity Resolution with self-supervised agents
The goal of Scoping is to reduce the space of candidate entity pairs by ranking, detecting, and removing unlinkable entities through outlier algorithms and self-supervised reusable autoencoders, leaving intact the set of true linkages.


# OC3-HR Dataset
The annotated multi-sourced entity linkage dataset is sourced from sample schemas from the following three database vendors:
- Oracle: https://github.com/oracle-samples/db-sample-schemas
- MySQL: https://www.mysqltutorial.org/mysql-sample-database.aspx
- HANA: https://github.com/saphanaacademy/HXE/tree/master/STS

- Category domain-specific: 3 x Orders-Customers schemas (Oracle, MySQL, SAP HANA)
- Category domain-agnostic: 1 additional Human-Resources schema (Oracle) 

![image](https://github.com/user-attachments/assets/c1fb8133-e570-4d0e-b524-11a892c4068d)


# Contact
leonard.traeger@umbc.edu for any related questions

### Reference

If you make advantage of the Collective Scoping method in your research, please cite the following in your manuscript:

@article{DBLP:journals/sncs/TraegerBK25,
  author       = {Leonard Traeger and Andreas Behrend and George Karabatis},
  title        = {Collective Scoping: Streamlining Entity Sets Towards Efficient and Effective Entity Linkages},
  journal      = {{SN} Comput. Sci.},
  volume       = {6},
  number       = {3},
  pages        = {238},
  year         = {2025},
  url          = {https://doi.org/10.1007/s42979-025-03734-7},
  doi          = {10.1007/S42979-025-03734-7}
}
