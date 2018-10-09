# Fullnode-via-Shell
Access OSC via shell

#open browser shell via ondemand.osc.edu
'''
ssh -X osu10342@owens.osc.edu
'''

#immediately afterwards type the following command:
'''
qsub -I -l nodes=1:ppn=28 -A PAS1407
'''
