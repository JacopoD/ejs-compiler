# ejs precompile

#### Usage: 

* how to add files or directories:

  ##### Add a file: 

  add an element to the files array (in ```settings.json```) with the path of the file you want to compile relative to ```ejs-compile.js``` , without ```./``` . Examples: if the file is in the same folder you would simply write ```filename.js``` if the file is in a subfolder you would write ```sub1/sub2/filename.js```

  

  ##### Add a directory:

  add an element to the dirs array (in ```settings.json```) with the path of the directory containing all the files you want to compile relative to ```ejs-compile.js``` , without ```./```  at the start of the string but with a ```/``` at the end. 


  ##### Set the output file

  In the file ```settings.json``` add the directory where the compiled file named views.js will be written, default is the same directory as ```ejs-compile.js```

  

* now you can run the file however you like and the compiled views will be written to ```public/js/views.js```

