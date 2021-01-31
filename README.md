The following flow I have learned during the VSD Sky130 OpenLANE workshop. I was aware prior to this workshop about directly running 
all the flow starting with Synthesis to Routing through the single script. This workshop had given me the insights on how to use openlane
interactively. 

1. How to use openlane in interactive mode

2. Interactive mode includes the following 

    1. Synthesis
    2. Floorplanning 
    3. Placement of the standard cells
    4. CTS : Clock Tree Synthesis 
    5. PDN : Power Distribution Network
    6. Routing 
    
3. This workshop also had taugt me how to build the standard cells in order to use with openlane flow, infact it is how standrd cell libraries are built.


Let me walk you through at first how do we do the entire flow that is starting from synthesis to routing of the design. 

STEPS: 

1. open the terminal in your ubutntu system and type the cd(change directory) so that you can go to your home directory 

      <img src="flow_images/step1.png" width="1000" height="300">
