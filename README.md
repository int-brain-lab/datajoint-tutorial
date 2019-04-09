# IBL Pipeline DataJoint Tutorial
In this tutorial, we briefly cover different ways by which you can work with and develop for the [DataJoint pipeline for the IBL project](https://github.com/int-brain-lab/ibl-pipeline). In this repository you'll a Jupyter notebook as well as a sample project that makes use of the IBL pipeline.

## Setting up

To use IBL pipeline, you will want to install IBL pipeline. You can install the latest packaged release of the pipeline with:

```bash
$ pip install ibl-pipeline
```



If you want to install the latest, un-released version of the pipeline, then you can install directly from the [GitHub source](https://github.com/int-brain-lab/ibl-pipeline):

```bash
$ pip install git+https://github.com/int-brain-lab/ibl-pipeline
```



Running any of the above will also install the necessary dependencies such as [DataJoint](https://github.com/datajoint/datajoint-python).



### To get DataJoint Diagram to work (optional)

In order for DataJoint Diagram (`dj.Diagram`) to work, you need to install [`graphviz`](https://graphviz.gitlab.io/download/) installed on your system. Please follow the [linked website](https://graphviz.gitlab.io/download/) to find the installation instruction specific to your operating system. 

## Using IBL pipeline

Once the `ibl_pipeline` package is installed via `pip`, you can start using it by importing subpackages from the `ibl_pipeline` as in:

```python
from ibl_pipeline import subject
```

This gives you access to `subject` module that contains DataJoint tables about the subjects.



