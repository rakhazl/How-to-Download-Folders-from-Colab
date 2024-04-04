# Hei Everyone :checkered_flag:

### 1. Open your _Google Colab_ in your computer
### 2. Assume that we want to download all the files under the sample_data folder. The first thing that we need to do is to create the zip file
    !zip -r path_your_files.zip path_your_files
#### Example :
![](https://github.com/rakhazl/How-to-Download-Folders-from-Colab/blob/main/Screenshot%20(571).png)
### Result code :
![](https://github.com/rakhazl/How-to-Download-Folders-from-Colab/blob/main/Screenshot%20(573).png)
### Your files in .zip
### 3. Download your files in .zip
    from google.colab import files
    files.download("your_path_files.zip")
### Example :
![](https://github.com/rakhazl/How-to-Download-Folders-from-Colab/blob/main/Screenshot%20(574).png)

## Congratulation 🚀
