# Visualizing Earth's Radiation Budget using NOAA Satellite Data

Instructor: Linus Andrae (landrae@iup.physik.uni-bremen.de)

Goal: To lean how to read, display, and interpret satellite data, such as the [Shortwave Radiation Budget](https://www.star.nesdis.noaa.gov/goesr/product_sw.php), using Python!

---
# Running this tutorial

Recommended:
You can run this code on the Uni Bremen Jupyter Notebook Server:
1. Go to jupyter.uni-bremen.de and login with your student credentials
2. Create a new Folder for the Climate Change 1 Module
3. Click on the Git Symbol (3rd from the top) in the left side bar
4. Select "Clone a Repository"
5. Enter: https://github.com/paradx/UHB-CC1-ERB and select "Clone"
6. Start with the Lesson.ipynb
7. Complete the assignment.ipynb
8. Upload your results to studip as a PDF(!) file.
   - Wrong formats (notebooks or word docs, etc.) will not be counted.
   - Name your File NAME_Assignment_CC1.pdf
   - Don't copy Results
   - Don't let ChatGPT (or any other LLM) do the work for you, if I have the feeling this is the case I might want to do a pair programming session with you 

If you really want to run the code on your own computer:

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
* Using Python on your device or a non uni jupyter server for this tutorial (I cannot /will not help troubleshoot)
* Using your operating system's Python or a shared Python installations unless you are advanced!

---
## Learning Resources

* [Project Pythia](https://projectpythia.org/) has some great resources for learning Python
* Learn more about [Python for Atmosphere and Ocean Scientists](https://carpentries-lab.github.io/python-aos-lesson/) using Software Carpentry lesson plans.
* I have a longer workshop, [Python for Earth Sciences with Rebekah](https://youtu.be/OjX1nDIWDh0), that was presented at the AGU 2022 Fall Meeting that is more beginner focused.
* Register for the short course at the [2023 AMS Annual Meeting](https://www.ametsoc.org/index.cfm/ams/education-careers/careers/professional-development/short-courses1/making-beautiful-images-of-noaa-satellite-data-using-python/
)! Virtual and in-person options available.
* Read this eBook about the topic [Earth observation using Python : a practical programming guide](https://umaryland.on.worldcat.org/oclc/1240265984) which is available for free from the UMD library.
