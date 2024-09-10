# Get SMM2 Level Details Using Only It's Level Code

With this easy to use R script, you will be able to get a `.csv` comprised of level information using only its level code. 

# How to Use

1. Create a `.csv` file with a list of levels you want details from. To make it easy, I like to just make a list in Excel/Google Sheets. Keep in mind that the API does not accept level codes with dashes in the name. So for example instead of writing down the level as `LEV-ELC-ODE`, you need to write it down as `LEVELCODE`.

![image](https://github.com/user-attachments/assets/65868447-b06e-4699-a6a1-c2826f398425) 

---

2. Replace `Line 26` in the code with the name of the file you just created!

![image](https://github.com/user-attachments/assets/c7599f66-6cde-4e4c-a3cb-3190bdd445a6)

---

3. Make sure the column name of your file matches the column name in `Line 71`. This is the column that the code is going to iterate through and send to the API.

![image](https://github.com/user-attachments/assets/3b18d651-77b6-4af8-8395-6ab2373c547d)

---

4. Export your new file!

![image](https://github.com/user-attachments/assets/090dd7d6-96fa-48fa-8241-5a974870ed57)

# Notes

There are more tags and information that one can pull from the SMM2 TGR API than the ones that I have included in this code. Feel free to visit the API website and explore! Modify this code to whatever fits your needs!




