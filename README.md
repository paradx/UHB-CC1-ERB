# Visualizing Earth's Radiation Budget using NOAA Satellite Data

Instructor: Rebekah Esmaili (bekah@umd.edu)

Goal: To lean how to read, display, and interpret satellite data, such as the [Shortwave Radiation Budget](https://www.star.nesdis.noaa.gov/goesr/product_sw.php), using Python!

---
# Running this tutorial

Recommended:

You do not need Python installed to work through this example. Click:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/modern-tools-workshop/UMD-ERB-tutorial/HEAD)


Need help with Binder? Video tutorial on [YouTube](https://youtu.be/3BrfFe4HsAw).


If you really want to run on your own computer:

* If you wish to run the examples locally, I recommend installing [Anaconda](https://www.anaconda.com/products/individual). If you are having trouble with your installation, contact the instructor before the course or use binder.
* Need help installing Anaconda? Video tutorial on [YouTube](https://youtu.be/zxSQCXXvOIM).
* Download the contents of the [GitHub repository](https://ter.ps/noaapy) to your computer.
* Launch Jupyter Notebooks from the Anaconda Navigator. This will open a window in your default browser. Navigate to the folder that contains the notebooks (*.ipynb) and click on the tutorial for the day.
* New to Jupyter? Here's a video tutorial on [YouTube](https://youtu.be/gmMCuR9JPpY).
* Additional packages:
  * Launch the Anaconda Prompt (Windows) or Terminal (MacOS/Linux). Then copy/paste and hit enter:
    ```
    conda install -c conda-forge cartopy
    ```

    Here's the full list of additional packages you'll need:
    - h5netcdf
    - cartopy
    - s3fs
    - xarray

  * If there are no errors, then you are set-up!
  * Alternatively, if you are familiar with environments, you can use the environments.yml to install the necessary packages. You can do this in the terminal using:

  ```
  conda env create -f environment.yml
  ```
  Then, switch to the new environment (conda activate python-workshop) once the installation is complete.

I *do not* recommend:
* Using Python on a remote server for this tutorial (I cannot help troubleshoot)
* Using your operating system's Python or a shared Python installations unless you are advanced!

---
## Learning Resources

* [Project Pythia](https://projectpythia.org/) has some great resources for learning Python
* Learn more about [Python for Atmosphere and Ocean Scientists](https://carpentries-lab.github.io/python-aos-lesson/) using Software Carpentry lesson plans.
* I have a longer workshop, [Python for Earth Sciences with Rebekah](https://youtu.be/OjX1nDIWDh0), that was presented at the AGU 2022 Fall Meeting that is more beginner focused.
* Register for the short course at the [2023 AMS Annual Meeting](https://www.ametsoc.org/index.cfm/ams/education-careers/careers/professional-development/short-courses1/making-beautiful-images-of-noaa-satellite-data-using-python/
)! Virtual and in-person options available.
* Read my eBook [Earth observation using Python : a practical programming guide](https://umaryland.on.worldcat.org/oclc/1240265984) which is available for free from the UMD library.
