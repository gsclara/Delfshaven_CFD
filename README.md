# Delfshaven_CFD
Delfshaven CFD simulations set-up for morphology analysis (ICWE2023 - abstract number 379) - URL: https://www.icwe2023.com/wordpress/wp-content/uploads/2023/07/icwe23-programmeSHORT2.pdf

The wind direction sin and cos are switched, so the name of the folder might not match the wind direction.

Steps to run a case: 
cd 0deg
surfaceFeatures
m4 system/blockMeshDict.m4 > system/blockMeshDict	# to modify your blockMesh, you need to change the .m4 file 
blockMesh
snappyHexMesh
simpleFoam
