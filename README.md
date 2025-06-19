# shortcut-tools
A repository of useful shortcut tools (iOS)

# Legend
**\[type]**: specifies type of argument for input or output
iOS supported types: text, number, list, dictionary, date, (other custom objects, e.g. file or note)

**\(description)**: Not literal variable or key name, simply a description of what should be inserted here by user

**Function only**: If yes, this shortcut may only be invoked with the needed input by another shortcut. Otherwise, the input will be interactively asked for.

***Input/output***: Lines in cursive are optional (usually used to specify given input is needed only for certain actions)

## Notes storage
A simplistic filesystem for text data based on the iOS notes app

### Supported operations

*Input/output for helper shortcuts*

- <ins>Read</ins>
  - **Input**: \[text] (filename)
  - **Output**: \[text] (file content)
- <ins>Write</ins>
  - **Input**: dictionary
    - \[text] filename: (filename)
    - \[text] data: (file content)
  - **Output**: (none)
- <ins>Delete</ins>
  - **Input**: \[text] (filename)
  - **Output**: (none)

### Included files:
- <ins>Storage</ins>: Main code logic
  - **Function only**: no
  - **Input**: dictionary
    - \[text] action: ("read"/"write"/"delete")
    - \[text] filename: (filename)
    - *\[text] data: (file content)*
  - **Output**: *see above*
    
- <ins>Storage (read)</ins>: Read helper function
  - **Function only**: yes
  - **Input+output**: *see above*
    
- <ins>Storage (write)</ins>: Write helper
  - **Function only**: yes
  - **Input+output**: *see above*
