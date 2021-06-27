# file Upload and Download
> You can Upload and Download files

|Angular|Typescript|Javascript|Html|CSS|
|---|---|---|---|---|

- Back end: https://github.com/Lee-Rhaan/File-Upload-and-Download-back-end

---

|Default Home Page|
|---|
- The message next to the button indicates if you have uploaded any files.
- It also shows the amount of files you've uploaded if you've already made prior uploads.
- You can upload Movies or whatever you'd like, no matter how big the file.
> The size limit of the uploads can be easily expandable in the "application.properties" file in the back end.
> At the moment I've set the "File Size" + "Request Size" to **100000000MB**
- I've kept the User Interface as clean and simple as possible, allowing the **end user** to rather focus more on the Functionality,
 than the Graphical Interface of the program.

![Screenshot (150)](https://user-images.githubusercontent.com/81378094/123540687-91448e00-d740-11eb-987c-ae1b0b107a34.png)

---

|Uploading Features:|
|---|
- Supports Single + Multi-file uploads
- Pressing the "Choose Files" button, takes you straight to the Home directory of the User that's Logged in on
the computer at the moment.

![Screenshot (151)](https://user-images.githubusercontent.com/81378094/123541685-06ff2880-d746-11eb-9981-b8c812cdaed0.png)

---

|Uploads|
|---|
- A Progress Bar pops up if you've finished your selection.
- It's just a nice added little feature to show the **end user** the progress of their existing upload.

![Screenshot (152)](https://user-images.githubusercontent.com/81378094/123542364-8e9a6680-d749-11eb-9447-ec5f3c34a6ba.png)

---

|Processed Files
|---|
- Your uploads gets highlighted in a green tab, with a download option.
> I've used a **Blob** (Binary Large Object) to store the uploads "which could be in any multimedia or file type" as **binary data**.

![Screenshot (153)](https://user-images.githubusercontent.com/81378094/123542567-973f6c80-d74a-11eb-89a2-e4d58ace2c4e.png)

---

|Small Feature|
|---|
- Another small feature i've added is that the colour of the file you hover your mouse across, turns red.

![Screenshot (154)](https://user-images.githubusercontent.com/81378094/123542942-94457b80-d74c-11eb-8221-53a6d43aa7ae.png)

---

|Download|
|---|
- A Progress Bar pops up if you pressed the **download button** on any one of the processed files.
- It's just a nice added little feature to show the **end user** the progress of their existing download.
> When you download an uploaded file, the binary data of that file gets **DESERIALIZED** back into an object (which in this case is a file). 

![Screenshot (155)](https://user-images.githubusercontent.com/81378094/123543132-6ca2e300-d74d-11eb-8a52-dc69bc6eab12.png)

---

|Download Path|
|---|
- Your downloaded files gets stored in your **Downloads** folder.
> If you look at the code in the back end, you'll tend to notice that the storage location of the downloaded files is in
"/Downloads/uploads/" location.
- So if you were to copy this code, then you'd just have to remove that uploads path, and change it to: "/Downloads/".
- Or, you could leave the code as it is, and create a folder in your Downloads named "uploads".

![Screenshot (157)](https://user-images.githubusercontent.com/81378094/123543889-fd2ef280-d750-11eb-8deb-8027fc405e02.png)

---
