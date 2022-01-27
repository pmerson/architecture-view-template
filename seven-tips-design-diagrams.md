# Seven Tips for Design Diagrams




### 1) Always add a notation key
- Don’t forget the colors and lines.
- Use a notation readers are familiar with or can readily understand.

### 2) Use distinct symbols for different types of elements and relations
- Ask yourself: what type of component is this? What type of connector is this?
- The answers go in the notation to make the diagram more expressive.

### 3) Use consistent symbology across diagrams of the same kind
- For each kind of diagram, you can define a notation key and copy & paste it around.
- It’s OK if your notation key shows symbols you didn't use in a diagram.
- Consistent symbols help: 
    - the readers to understand the diagram more easily;
    - the writers who don’t need to "invent" a new notation every time.
- Similarly, a consistent structure (template) for technical documents help readers and writers.


### 4) If you use an architecture style or pattern, make that clear
- Mention the pattern in the view name, the diagram itself, or in the prose around it.
- Ex.: in a design that uses MVC the boxes should be identifiable as model, view, or controller.
- This tip may sound nit-picking, but it's a very common cause for ambiguity and confusion in design diagrams. 

### 5) Do not use double arrows for call-return or send-receive interactions
- Otherwise, you can’t tell who is calling whom!
- In call-return, it’s implicit that there's data in the request and in the response. Therefore, there's no need to use double arrows to indicate data flow. 

### 6) Keep the diagram up-to-date or delete it
- Diagrams (and any accompanying prose) are created to aid the design discussion.
- Once the code is written, the diagram has served its main purpose.
- It's common for code sooner or later to differ from the original design. What to do?
   - Ideally, you should update the diagram.
   - When updating is not worth the effort, delete the diagram. It can be a "physical" or "logical" delete (ex.: add an "out-of-date" stamp/comment/sign).
   - The worst option is to leave the diagram as is.

### 7) Use refinement to avoid large, complex diagrams
- Create high level diagrams where boxes represent subsystems, layers, BCs, or other abstract groupings of elements.
- Then use refinement to create diagrams that show the internal elements. 
