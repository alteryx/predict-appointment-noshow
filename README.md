# Using Featuretools to Predict Missed Appointments

<a style="margin:30px" href="https://www.featuretools.com">
    <img width=50% src="https://www.featuretools.com/wp-content/uploads/2017/12/FeatureLabs-Logo-Tangerine-800.png" alt="Featuretools" />
</a>

In this tutorial, we show how [Featuretools](https://www.featuretools.com) can be used to predict whether or not a patient will show up to a scheduled appointment using a [dataset](https://www.kaggle.com/joniarroba/noshowappointments) from Kaggle. We make all of the features from the most popular [kernel](https://www.kaggle.com/somrikbanerjee/predicting-show-up-no-show) on kaggle, and make some other interesting features automatically.

*The Tutorial notebook from this repository exists [on Kaggle](https://www.kaggle.com/sjrothsc/using-featuretools-for-missed-appointments). If you would prefer to work in that environment, you can fork the existing kernel to use as a starting point.*

## Highlights

* We generate interesting aggregations by age and location automatically.
* We use a secondary time index to generate features from the no-show column without leaking invalid information.


## Running the tutorial
If you would like to work on Kaggle, the Tutorial notebook [has been uploaded](https://www.kaggle.com/sjrothsc/using-featuretools-for-missed-appointments) as a kernel. You can fork that notebook to use as a starting point. If you prefer to work locally:

1. Clone the repo

    ```
    git clone https://github.com/Featuretools/predict-appointment-noshow.git
    ```

2. Install the requirements

    ```
    pip install -r requirements.txt
    ```
    
    *You will also need to install **graphviz** for this demo. Please install graphviz according to the instructions in the [Featuretools Documentation](https://docs.featuretools.com/getting_started/install.html)*

3. Download the data

    You can download the data from [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments) or create a kernel and use Featuretools there. After downloading, save the CSV to a directory called `data` in the root of this repository.

4. Run the [Tutorial](Tutorial.ipynb) using Jupyter

    ```
    jupyter notebook
    ```

## Feature Labs
<a href="https://www.featurelabs.com/">
    <img src="http://www.featurelabs.com/wp-content/uploads/2017/12/logo.png" alt="Featuretools" />
</a>

Featuretools is an open source project created by [Feature Labs](https://www.featurelabs.com/). To see the other open source projects we're working on visit Feature Labs [Open Source](https://www.featurelabs.com/open). If building impactful data science pipelines is important to you or your business, please [get in touch](https://www.featurelabs.com/contact).

### Contact

Any questions can be directed to help@featurelabs.com
