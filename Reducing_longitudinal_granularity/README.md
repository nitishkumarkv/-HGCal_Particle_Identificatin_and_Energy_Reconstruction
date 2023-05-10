create_pkl_files.ipynb : creates new reduced rechit_x, rechit_y, rechit_z, rechit_ene for reduced longitudinal granularity of different sections. The rechits are reduced to one layer in each section and the rechit energy is added for rechits with the same x-y position.


create_pkl_files_red_CEE.ipynb: integrate along z-axis only for CE-E section

create_pkl_files_red_CEH.ipynb: integrate along z-axis only for CE-H section

create_pkl_files_red_all.ipynb: integrate along z-axis only for all sections

These codes only created the new rechit x,y,z,E. For creating pickle files for training, follow the DRN source code.
