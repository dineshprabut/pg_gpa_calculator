# Welcome to GPA CALCULATOR !
A Simple GPA calculator using PyQt5.

### Files 
First you have install PyQt5 in your Python Version 3 using Command prompt.

## What are the packages to be installed

**PyQt5**
**auto-py-to-exe**

## Create files and folders

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **AUPGGPA.ui** button in the file explorer. You can also create folders by clicking the **GPA** button.

## Switch to another file

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Convert .ui to .py

You want to convert .ui file to .py by clicking **Command Prompt**. You have to type **cd  >Location of the file<** and click enter.Now you have to type   **pyuic5 -x Filename.ui - o Filename.py** and click enter. Now python has been created.


# Source Code 
You have to type the following code under
 **def retranslateUi(self, AnnaUniersityGPACalculater):**

```self.comboBox.addItems(["O", "A+", "A", "B+", "B"])  
self.comboBox_2.addItems(["O", "A+", "A", "B+", "B"])  
self.comboBox_3.addItems(["O", "A+", "A", "B+", "B"])  
self.comboBox_4.addItems(["O", "A+", "A", "B+", "B"])  
self.comboBox_5.addItems(["O", "A+", "A", "B+", "B"])  
self.comboBox_6.addItems(["O", "A+", "A", "B+", "B"])  
  
self.spinBox.setMaximum(4)  
self.spinBox.setMinimum(1)  
self.spinBox_2.setMaximum(4)  
self.spinBox_2.setMinimum(1)  
self.spinBox_3.setMaximum(4)  
self.spinBox_3.setMinimum(1)  
self.spinBox_4.setMaximum(4)  
self.spinBox_4.setMinimum(1)  
self.spinBox_5.setMaximum(4)  
self.spinBox_5.setMinimum(1)  
self.spinBox_6.setMaximum(4)  
self.spinBox_6.setMinimum(1)  
self.pushButton.clicked.connect(calculateGPA)
```

## Run 
You can run the file in pycharm or Microsoft visual studio before convert to .exe. Using this you can check whether the application is working correctly or not.

## Convert .py file into .exe 
 You want to convert .py file to .exe by clicking **Command Prompt**. You have to type **auto-py-to-exe** and click enter.Now you can see the dialog box.In the dialog box, you have to upload the file which you to convert to .exe in the path to file option.
1. If you want only .exe file means do this **Onefile > One File option**
2. If you want to hide the console means do this **Console Window > Window Based (hide the console) 
3. You can add Icon for you application by clicking the icon option
Now click **CONVERT TO .PY TO .EXE **.

## Open a file

You can open a file from where you have save the .exe file by double clicking the file or clicking **Open from**.

## Conclusion 
After you have opened the exe file, you may find like below:


![Capture](https://user-images.githubusercontent.com/71083334/95010887-7d08b000-064a-11eb-83fa-1f41b738dd91.JPG) 

