A Full end to end solution using Fabric Lakehouse

0- Create a Fabric Workspace

1- Create a lakehouse

2-Download the notebook from Github and import it to Fabric Workspace

3-open a notebook, attached it to the Lakehouse

4-Run the notebook in sequence just to have the initial load ( you may want to change Nbr_Files_to_Download to a bigger numbers, the data source for 5 minutes is kept only for two days, the 24 hours is only for 2 Months, I have the 5 years worth of data but I don't know how to share it with a minimum cost)

add a schedule for those notebooks,  5 minutes and  24 Hours get a new files only at 6 AM Brisbane time

## PowerBI
an import model pbix is provided, alternatively you can run a script to comvert the pbix to a direct lake mode


<img width="733" alt="image" src="https://github.com/djouallah/aemo_fabric/assets/12554469/62a5ac05-34b7-4ad8-af74-6d8d92a211a3">

