## Exercise 1

### Exporting

You can also export a project. This is helpful, for instance, if you wanted to send your raw data and cleaning steps to a collaborator, or share this information as a supplement to a publication.

1. Click the <code>Export</code> button in the top right and select <code>OpenRefine project archive to file</code>.
1. A <code>tar.gz</code> file will download to your default <code>Download</code> directory. Depending on your browser you may have to confirm that you want to save the file. The <code>tar.gz</code> extension tells you that this is a compressed file. The downloaded <code>tar.gz</code> file is actually a folder of files which have been compressed. Linux and Mac machines will have software installed to automatically expand this type of file when you double-click on it. For Windows based machines you may have to install a utility like ‘7-zip’ in order to expand the file and see the files in the folder.
1. After you have expanded the file look at the files that appear in this folder. What files are here? What information do you think these files contain?

<details>
  <summary>
  Solution
  </summary>
  
    You should see:

  - a <code>history</code> folder which contains a collection of <code>zip</code> files. Each of these files itself contains a <code>change.txt</code> file. These <code>change.txt</code> files are the records of each individual transformation that you did to your data.
  - a <code>data.zip</code> file. When expanded, this <code>zip</code> file includes a file called <code>data.txt</code> which is a copy of your raw data. You may also see other files.

</details>

[Episode 6 Key Points](episode6_key.md)
