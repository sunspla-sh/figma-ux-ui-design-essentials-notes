# Prototyping - Level 2

## How to Add a Popup Overlay Modal

1. Switch from design mode to prototype mode by navigating from the design panel to the prototype panel

2. Create a flow connecting one of the frames representing a page to one of the frames representing a popup modal

3. In the prototype panel (after creating the flow connection between the two frames), add an interaction with an "open overlay" action that occurs either "on click" or "after delay" to trigger the appearance of the popup modal frame in the center of the page frame

## How to Make and Prototype a Tool Tip

1. Switch from design mode to prototype mode by navigating from the design panel to the prototype panel

2. Create a flow connecting one of the frames representing an information icon on any page to one of the frames representing a tooltip

3. In the prototype panel (after creating the flow connection between the two frames), add an interaction with an "open overlay" action that occurs "on click" to trigger the appearance of the tooltip frame above the informational icon that was clicked on the page page frame

4. Make sure the tooltip frame is positioned directly above the informational icon so that it appears to be connected to the icon when the user clicks on the informational icon

## What are Flows?

- A flow is a series of interactions that navigate between pages (represented by frames) or individual frames on a single page to simulate a user completing a task in an application

## Slide-in Mobile Nav Menu Overlay

- Nav menus can be added using the same concepts learned in the popup overlay modal section

    1. Create a flow connecting the nav menu button to a frame representing the nav menu

    2. In the prototype panel (after creating the flow connection between the two frames), add an interaction with an "open overlay" action that occurs "on click" to trigger the appearance of the nav menu frame

    3. Make sure the nav menu frame slides in on the left or right of the screen rather than appearing in the center of the screen (and optionally adjust the overlay settings so that clicking outside of the overlay will close it)

## Class Project 17 - Prototyping

- Add a newsletter signup modal flow, a tooltip for credit card info flow,  and a mobile navigation menu flow

## How to Pin Navigation to Top

- To pin our menu/navigation bar to the top of the screen, select the frame containing the menu/navigation bar, switch from the Design panel to the Prototype panel, and choose the "sticky" value of the Position property within the Scroll Behavior section

- Generically, after selecting any frame, you can change that specific frame's scroll behavior by going to the Prototype panel and adjust settings as desired within the Scroll Behavior section (e.g. choose position "fixed", "sticky" or "scroll with parent")

## How to Make Horizontal Scrolling Swipe

- Add objects that extend outside of the parent frame and then choose the "Horizontal" value of the Overflow property within the Scroll Behavior section

## Automatic Scroll Down a Page to Anchor Point

- Create a flow connecting a button to a different object within the same frame, using "scroll" as the action and "on click" as the trigger