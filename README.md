#THIS SCRIPT MAINLY CREATED FOR UPDATE LAUNCH CONFIG USERDATA

#THATS SCRIPT RUN USING AWS_CLI SO YOU NEED TO CONFIGURED FIRST AWS_CLI CONFIG 

# ThEN YOU NEED TO UPDATE ASG GROUPS IN asg_var  

#RUN genrate_userdata_from_lc THAT WILL GENRATE userdata of LC which associate with ASG
#UPDATE USERDATA AS REQUIRED
#RUN  create-lc-and-update-asg THAT WILL CREATE NEW LC WITH UPDATE USERDATA AND ADD TO ASG

#IF YOU ARE CREATING MULTIPLE LC IN A DAY YOU HAVE TO CHANGE DATA VARIABLE BECAUSE NEWLY CREATE BY DATE IN NAME
#YOU CAN UPDATE DATE VARIABLE LIKE THIS

#DATE=`date +%Y%m%d-1`
#DATE=`date +%Y%m%d-2`
