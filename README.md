# just_trial
Let me try to document my cybersec journey

# Linux Luminary

<h5>Data manipulation</h5>
<h6>Translating a Character with a "tr" </h6>
<img width="1063" height="475" alt="Screenshot 2026-10-15 at 15-42-38 pwn college" src="https://github.com/user-attachments/assets/85e8f904-775b-4e88-9cc3-d81c990311a9" />


<h5>Deleting Character</h5>
<h6>"tr" combined with the flag "-d" can also delete unwanted character</h6>
<img width="1063" height="475" alt="Screenshot 2026-10-15 at 15-33-57 pwn college" src="https://github.com/user-attachments/assets/7147bd75-3c51-4b3f-a522-b7f1fee6b866" />

<h5>Deleting Newlines</h5>
<h6>"tr" combined with the flag "-d" and "\n" will give you the flag</h6>
<img width="1063" height="475" alt="Screenshot 2026-10-15 at 15-47-23 pwn college" src="https://github.com/user-attachments/assets/54c5093b-cc04-4860-87bb-a3776a86907e" />

<h5>Extracting the first lines with head</h5>
<h6>The "head" command is used to display the first few lines of its input, and "head -n 2" grabs the first two lines in the head</h6>
<img width="1063" height="475" alt="Screenshot 2026-10-15 at 15-54-31 pwn college" src="https://github.com/user-attachments/assets/266920be-c8a2-4834-8c0a-913db3e7765c" />

<h5>Extracting Specific section of text<h5>
<h6>You could use cut to extract specific columns:</h6>
<img width="1238" height="540" alt="Screenshot 2026-10-15 at 15-57-56 pwn college" src="https://github.com/user-attachments/assets/410b8782-7a3b-4eb9-a3ce-8f764fde6449" />

<h5>Sorting Data</h5>
<h6>"sort" is the command: By default, sort orders lines alphabetically. Arguments can change this:

    -r: reverse order (Z to A)
    -n: numeric sort (for numbers)
    -u: unique lines only (remove duplicates)
    -R: random order!
</h6>

<img width="1063" height="475" alt="Screenshot 2026-10-15 at 16-08-45 pwn college" src="https://github.com/user-attachments/assets/77b3020f-9169-487a-b325-7e76038c7fee" />


