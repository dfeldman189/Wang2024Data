1. data for difference in control and Cntnap2:
Control_animals_data.mat
Cntnap2Null_animals_data.mat

data were arranged as structure array:

WT_animal_X.(noise condition).(image field #).trace.(ROI name).whisker: m*n array, m:individual trial, n:dF/F trace (1:8=baseline; 9:19=prestimulus period; 20:27=evoked activity) 


WT_animal_X.(noise condition).(image field #).location.(ROI name).realTheta: real angle of the cell in whisker array, relative the center of barrel (e3 e2 e1 d3 d2 d1 c3 c2 c1)

WT_animal_X.(noise condition).(image field #).location.(ROI name).theta: normalized angle of the cell in whisker array, relative the center of barrel (e3 e2 e1 d3 d2 d1 c3 c2 c1)

WT_animal_X.(noise condition).(image field #).location.(ROI name).realR: real distance(micron) of the cell in whisker array, relative the center of barrel (e3 e2 e1 d3 d2 d1 c3 c2 c1)

WT_animal_X.(noise condition).(image field #).location.(ROI name).R: normalized distance of the cell in whisker array, relative the center of barrel (e3 e2 e1 d3 d2 d1 c3 c2 c1)


Cntnap2Null_animal_X is the same structure



2. data for difference in longitudinal imaging of control and Cntnap2:
Control_animals_longitudinal_imaging_data.mat
Cntnap2Null_animals_longitudinal_imaging_data.mat

data were arranged as structure array:

WT_animal_X.(image field #).(session #).trace.(ROI name).whisker: m*n array, m:individual trial, n:dF/F trace (1:8=baseline; 9:19=prestimulus period; 20:27=evoked activity)

WT_animal_X.(image field #).(session #).location.(ROI name).realTheta: real angle of the cell in whisker array, relative the center of barrel (e3 e2 e1 d3 d2 d1 c3 c2 c1)

WT_animal_X.(image field #).(session #).location.(ROI name).theta: normalized angle of the cell in whisker array, relative the center of barrel (e3 e2 e1 d3 d2 d1 c3 c2 c1)

WT_animal_X.(image field #).(session #).location.(ROI name).realR: real distance(micron) of the cell in whisker array, relative the center of barrel (e3 e2 e1 d3 d2 d1 c3 c2 c1)

WT_animal_X.(image field #).(session #).location.(ROI name).R: normalized distance of the cell in whisker array, relative the center of barrel (e3 e2 e1 d3 d2 d1 c3 c2 c1)

WT_animal_X.(image field #).(session #).pairs: n*2 array; ROI(n,1) in session1 is ROI(n,2) in session 2

Cntnap2Null_animal_X is the same structure

