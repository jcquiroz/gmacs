Currently, only the first three models are being evaluated:

Model     | Description
----------|--------------
`model_1` | “Gmacs base”: Gmacs base matches the current BBRKC assessment model in configuration as closely as possible
`model_2` | "Free Q": catchability for BSFRF survey is estimated rather than being fixed at 1 ($q_phz = 4$ for BSFRF)
`model_3` | “Variable M”: estimates natural mortality (M) using a time-varying, random walk configuration rather than the time blocks used in the base model
`model_4` | 
`model_M` | 

Take a look at each model's `bbrkc.ctl` file to see how the differences are implemented
