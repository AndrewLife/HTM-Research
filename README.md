# HTM-Research
Implementation of HTM with NAB dataset researching real time anomaly detection

HTM motivation and fundamentals series:
https://www.youtube.com/watch?v=XMB0ri4qgwc&list=PL3yXMgtrZmDqhsFQzwUC9V8MeeVOQ7eZ9

Set up Nupic in Ubuntu 14:
http://nupic.docs.numenta.org/1.0.4/quick-start/index.html
In addition to the link above, you may need this link to assist in setting up python2.7, pip, and other required packages:
https://gist.github.com/rhyolight/15b8454780424f690d00

Once you set up nupic on Ubuntu 14, I followed the OPF source code at this link:
http://nupic.docs.numenta.org/1.0.4/quick-start/opf.html

Before running the source code, you need to create a model.yaml file that sets up the parameters for HTM's system:
http://nupic.docs.numenta.org/1.0.4/quick-start/example-model-params.html

Results that will show at this point are one step prediction and a five step prediction along with a confidence level percentage.
