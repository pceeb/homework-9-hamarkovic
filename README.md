# Homework 10

You will fill out the following
questionnaire for each program and submit the answers as your final homework. You will
also share your questionnaire with the group that created the program __by the end of discussion__.
---

PhyloMicro = PM
https://github.com/lennicec/CspilurusMicrobiome_EEB177Project
FishGut = FG
https://github.com/j4100briggs/Fish-Gut-dataProject199


### The Readme

#### 1. Is the Readme file the first document displayed upon lading the Github?  Does this Readme page include a title, and the name and contact information for all project members?

PM: Yes, the Readme is the first document displayed. There is a title and name, but not contact information.

FG: Yes, the Readme is the first document displayed. There is a title, names, and contact information.

#### 2. Is the purpose of this program clear from the Introduction?  What -in your own words- is the motivation behind the program.

PM: The purpose is clear. The motivation is to analyze the phylogeny of bacteria from fish gut extractions.

FG: Yes, the purpose is clear. The program condenses sequencing data and turns it into a Phyloseq object in R.

#### 3. Is there a program workflow and is it easy to understand?  What -in your own words- is the program workflow?

PM: Yes, there is a program workflow, but it would be easier to understand if it didn't use jargon or if the jargon was explained. It seems like the program removes low quality sequence results, and then creates phylogenies from the remaining sequencing results. I don;t know what an emperor plot is.

FG: Yes, there is an easy-to-understand workflow for the bash scripts. The program cuts and sorts the input data, and then combines the sorted files into a single file which is the input to the R script. The R code converts the input into matrices and then makes these into a PhyloSeq object.

#### 4. Are the dependencies indicated in the workflow?  If there are Hoffman2 specific requirements are they indicated?

PM: Yes, the dependencies are listed. Yes, Hoffman2 requirements are indicated. 

FG: Yes, dependencies are clearly listed, and Hoffman2 requirements are indicated, with helpful instructions as well.

#### 5. Are there instructions for running the program?  Do the instructions make sense?  What would you do to improve the instructions?

PM: Yes, there are instructions and they make sense. I think the instructions are good, and the commands are provided. 

FG: Yes, there are clear instructions for running the program. You have to choose between damfish_script and damfish_script_filler, right? So just make it more clear in the instructions.

#### 6. Is there a section that indicates the files and directories produced by the program?

PM: Yes, there is a section with outputs.

FG: Outputs are listed, but not in their own section, and they could be described further (just another sentence or two).

#### 7. Are the research programs / motivations for the program cited?  Are the dependencies cited?

PM: No, I don't see the motivation for the program. There are references.

FG: The motivations could be explained a bit further - for instance, add a specific example of a project the program could be used for. Dependencies are cited clearly.

---

### The Scripts

#### 8. Is there a directory that contains all of the program scripts?

PM: Yes, there is a directory with scripts.

FG: The scripts are on the github page, but not in their own directory..

#### 9. Do these programs generate a run log?

N/A

---

### The Vignette

#### 10. Is there a directory called Vignette and does it include a test set, the commands used to run the program and the expected output databases?

PM: Yes, there is a vignette directory and it includes those.

FG: Yes, there is a vignette directory and it includes those.

#### 11. Where you able to run the Vignette using the small test dataset? If not what errors did you get?  If so was it easy to run the dataset?  Where the instructions clear.

PM: I didn't try to run it because I don't have Quiime.

FG: Yes, I was able to run it, and to me it looks like the output was right. It took a long time to install the "phyloseq" package - 15 minutes probably. It was easy to run with the included commands.

#### 12. Where you able to reproduce the expected output?  If not what was different.

PM: N/A

FG: Yes, it looked right to me :)

---

### General

#### 13. Give __at least two__ suggestions for ways to improve the GitHub page or the operation of the program.

PM: I think it would be good to include the motivation/uses of the program (not just what it does). For the command that starts the master.sh file, I think it would be good to have some of those variables be provided within the program if possible, so the user wouldnt have to copy such a long thing to run it.

FG: Make sure the formatting isn't messed up after the Hoffman2 package instructions. Also, you should use some headers (#) in the markdown file so the sections are clearer.
