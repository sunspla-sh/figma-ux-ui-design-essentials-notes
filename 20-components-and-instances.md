# Components and Instances

## What are Components?

- Components are reusable objects in Figma with a master version and instance versions that receive updates from the master

## Updating, Changing, and Resetting Components

- Updates to properties of the master component automatically flow down to the instance components

- Alterations to instance components can be made without affecting the master component, so that they are no longer identical

- In the event that you prefer the look of an edited instance component over the original master component, you can push changes from instance components back up to the master component if desired

- Right clicking on an instance component opens up a dropdown menu with an option to revert all styles to match the master component

## You Can't Kill Main Components

- To fully remove a component, you must delete the master version and all instance versions of that component, otherwise the master version can always be restored from the instance versions

- Components can be brought in from other Figma files

    - When a component is brought into your current working file from a different Figma file, it will not automatically update the instance component when the master component is changed in that other file

        - To get master component changes to flow through to instance components when they are in separate files, a Team Library must be used from the paid Figma subscription

## Where Should You Keep Main Components?

- Best practice is to keep the master versions of your components on a separate component page

## Intro to Forward Slash (/) Naming Convention

- Forward slashes in component names create a hierarchy in the components tab of the assets panel and will allow for the grouping of components

    - For example, two components named "Arrow / Left" and "Arrow / Right" will be grouped into an "Arrow" section within the components tab of the assets panel

## Class Project 14 - Components

- Create a new page called components, then add a light mode and a dark mode version of the same component to the components page

    - Use the forward slash naming convention to group them within the components tab of the assets panel