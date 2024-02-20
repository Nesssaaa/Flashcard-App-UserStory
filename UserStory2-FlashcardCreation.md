## User Story -2 Flashcard Creation

## Value Preposition

As an student
I want to add my own Flashcards with my own pairs of words
So that I can learn my own subjects

## Description

![Image for User Story 2](./imgFlashCardCreation.png)

## Acceptance criteria

- [ ] user see the Navigation bar on the bottom with the Homepage-Link and the "new Cards"-Link on all pages
- [ ] by clicking on navigation icon to create new card, you see a form and a button to submit
- [ ] user can write your own pair of words an submit them



## Tasks

- [ ] Create a new branch "FlashcardCreation"
- [ ] Create a Navigation Component
- [ ] Create a Layout Component with the prop "children", wich returns the Header and the Navigation Components. 
- [ ] The Layout Component is returned in _app.js
- [ ] Create a NewCard Component wich returns a form and a submit-button
- [ ] The NewCard Component is returned in pages/ index.js
- [ ] The form-fields are required
- [ ] reset form with event.target.reset(), add focus with event.target.elements.question.focus()
