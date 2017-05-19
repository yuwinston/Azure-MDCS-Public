# Create a new MDCS cluster under a new AD Forest

This template will deploy a new MDCS cluster under a new Azure based domain. It include three steps

1. Create a new Windows VM and create a new AD Forest, Domain and DC, the DC will also act as MATLAB/MDCS license server:

http://insidelabs-git.mathworks.com/wyu/Azure-MDCS/tree/master/active-directory-new-domain

2. Create a Frontend edge node which have MATLAB client installed and join into Domain 

https://github.com/yuwinston/Azure-MDCS-Public/tree/master/create_edge_node

3. Create a HPC cluster which contains MDCS installation

https://github.com/yuwinston/Azure-MDCS-Public/tree/master/create-hpc-cluster-custom-image