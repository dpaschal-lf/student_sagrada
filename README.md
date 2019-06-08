# student_sagrada

### component breakdown

#### SagradaGame - represents the entire game controller
  - properties
    - diceBag - array, stores dice to be pulled by players
    - players - array of players
    - currentPlayer - int of current player
  - methods
    - addPlayer
      - params : name, boardGuide (the cans and cants for the window), favorTokenCount
      - returns : nothing
      - modifies : players
    

#### SagradaPlayer - represents each player in the game
  - properties
    - name
    - windowSlots - multidimensional array of slots
  - methods
    - makeWindowSlots
      - params : boardGuide for slots
      - returns : none
      - modifies : windowSlots
    - checkWindowSlot
      - params: x and y position
      - returns: false if out of bounds, restrictions
  
#### SagradaSlot - represents the slots for dice on the player board
  - properties
    - restriction
  - methods
  
#### SagradaDie - represents the dice in the sagrada game
  - properties
  - methods
