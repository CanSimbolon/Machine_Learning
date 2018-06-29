#Jupyter Notebook 

To make your jupyter notebook open web brower 
automatically, run these commands on the command line. 

```
# list all files 
- ls -a 
# edit this file 
- vi .bash_profile
# add this line and save
- export BROWSER=open
``` 
Now you should be good to go. 

reference: https://medium.com/@GalarnykMichael/install-spark-on-mac-pyspark-453f395f240b

## Random
If your notebook gives you error "IOPub data rate exceeded", try: 
`jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10`

## Images in Markdown 
```
<img src="images/image2.jpeg"  style="width:400px;">
```

## Red Font 
```
<span style="color:red">some **This is Red Bold.** text</span>
```
[Reference](https://stackoverflow.com/questions/35465557/how-to-apply-color-in-markdown)
