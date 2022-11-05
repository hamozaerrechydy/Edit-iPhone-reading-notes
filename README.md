# Edit iPhone reading notes 📚

When I import my reading notes 📒 from my iPhone to the computer via email 📫 I get a very messy document of notes that looks like this : 

October 28, 2022
Introduction
the essence of writing is rewriting.

October 28, 2022
2. Simplicity
If the reader is lost, it’s usually because the writer hasn’t been careful enough.

October 29, 2022
2. Simplicity
Writers must therefore constantly ask: what am I trying to say? Surprisingly often they don’t know. Then they must look at what they have written and ask: have I said it?

## How to fix that? 

Well, all it takes is few commands on the command line 💻. 

### Create a txt file 📄

Here's how to do it on the command line : 

touch [fine name].txt

### Now run the editing commands  📝

sed -i '/pattern/d' filename 

Replace the pattern with a regex that matches the lines you want to delete from your notes, regex if you don't know is just a weird looking code that you type and matches some pieces of text in a doc. 

Check out this [question](https://stackoverflow.com/questions/5410757/how-to-delete-from-a-text-file-all-lines-that-contain-a-specific-string) on stack overflow to learn more about using the terminal to edit your txt docs.  
