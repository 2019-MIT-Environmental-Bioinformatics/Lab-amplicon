# Today in class:
1.
2.




## Install qiime2
*if you use this tutorial to install qiime2 after November 2019, check the qiime2 webpage for the [latest qiime 2 version][2]*

Login to poseidon and navigate to your Lab directory

Get the yml file from the qiime2 webpage:

```wget https://data.qiime2.org/distro/core/qiime2-2019.7-py36-linux-conda.yml```

and then use this file to create your conda envinment:

```conda env create -n qiime2-2019.7 --file qiime2-2019.7-py36-linux-conda.yml```

Activate the conda environment you just created and test the installation by typing calling qiime and asking it to display the help menu:
```qiime --help```



[2]: https://docs.qiime2.org/2019.7/install/native/
