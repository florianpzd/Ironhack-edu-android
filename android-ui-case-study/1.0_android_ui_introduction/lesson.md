# Lesson 1.0: Android UI system introduction

### Lesson Duration: 3 hours

> Purpose: The goal of this lesson is to introduce the layout and view system on Android, and to introduce students to the two ways of creating them in Android Studio.

---

### Prerequisites

Before starting this lesson, students are expected to know the basics of of the Android studio software. They are supposed to have the software installed on their machine, with an emulator created to be able to run the applications they will develop. They are able to create a project from scratch and understand the notions of SDK, package etc. They are able to launch an application on an emulator and know the basics parts of an android project: res folder, java folder, .gradle file

### Learning Objectives

After this lesson, students will be able to:

- Understand the view concept on Android
- Understand what is a Widget
- Understand the concept of layout and know what is a relative layout, a linear layout and a frame layout
- Be able to create a simple view with constraints on widgets (size, positioning, simple attributes) using the graphical tool but also in XML

---

### Introduction
> :clock10: 20 min

Quick check of the prerequisites: creation of a MCQ using the kahoot.com platform, about ten questions. 
Take a break between each question to answer the different questions from the students.  

Examples of questions:
- What is an emulator
- What is the role of the SDK
- What is the role of the package
- What are the different types of folders in an Android project?


### Lesson 1 key concepts

> :clock10: 30 min

Graphic way to create Android views

- Presentation of the main widget types and some attributes: Textview, Edittextview, Imageview, Button
- Quick introduction to widget size concepts: dp, wrap content, match parent
- Presentation of the android graphic tool to create a view
---

:coffee: **BREAK**

---

#### :pencil2: Check for Understanding - Class activity/quick quiz

> :clock10: 10 min (+ 10 min Review)

**Activity 1**
Creation of a view containing some widgets previously seen:
- A **Textview** with Hello World and blue color at the top left of the screen
- An **Imageview** of size 150dp * 150dp with an imported image of their choice at the bottom right of the screen
- A **Button** that makes the whole size in length of the screen whatever the screen in the middle of the screen, with the text: click me

The notion of widget positioning should be found on the Internet but will be reviewed and deepened in **lesson 3**

</details>

<details>
  <summary> Click for Solution: Activity 1 solutions </summary>

- Link to [activity 1 solution](https://gist.github.com/ironhack-edu/253270833e1716fca5d7273469ea757d).

</details>

---

:coffee: **BREAK**

---

### Lesson 2 key concepts

> :clock10: 20 min

XML way to create Android Views

- Specificity of the XML file format 
- Presentation of the different attributes and widgets in XML
- UI preview system

---

#### :pencil2: Check for Understanding - Class activity/quick quiz

> :clock10: 10 min (+ 10 min Review)

**Activity 2**
Creation of a view containing some widgets previously seen:
- A **TextView** with Hello World and blue color at the top left of the screen
- An **ImageView** of size 150dp * 150dp with an imported image of their choice at the bottom right of the screen
- A **Button** that makes the whole size in length of the screen whatever the screen in the middle of the screen, with the text: click me

The notion of widget positioning should be found on the Internet but will be reviewed and deepened in **xx@**
<details>
  <summary> Click for Solution: Activity 2 solutions </summary>

- Link to [activity 2 solutions](https://gist.github.com/ironhack-edu/2946a99a19aa1f86c066e7dd1ffec7fc).

</details>

---

:coffee: **BREAK**

---

### Lesson 3 key concepts

> :clock10: 20 min

- Presentation of the different types of basic layout (Relative Layout, Linear Layout, Frame Layout)
- Explanation of the widget positioning system
- Explanation of the margin and padding system
- Explanation of the problem caused by nested layouts (opening to constraint layout)

---

### :pencil2: Check for Understanding - Class activity/quick quiz

> :clock10: 30 min

 **Activity 3**:

- Creation of a **Button** at the top left of the screen of size 50dp * 50dp
- Creation of a **Button** to the right of the first button located at 20dp * 20dp from the latter
- Create an **ImageView** below the first button with a length equal to the screen size
- Create a **Textview** in the center of this image (using frame layout)

<details>
  <summary>Click for Solution: Activity 3 solutions</summary>

- Link to [activity 3 solution](https://github.com/florianpzd/Ironhack-edu-android/blob/master/android-ui-case-study/1.0_android_ui_introduction/exercise3/view.xml).

</details>

---



:coffee: **BREAK**

---

### :pencil2: Practice on key concepts - Lab

> :clock10: 30 min

Creation of a view with the tool they prefer.
This view must contain:

- Three **Button** each 1/3 the length of the screen at the bottom of the screen (using the linear layout). These buttons must be of three different colors.
- An **ImageView** of size 200d * 200dp in the center of the screen
- A **TextView** below this image of size 18 sp. The text should be about three lines long but should not go beyond the right edge of the image, nor the left edge.
- An **EditTextView** at the top right of the screen, this last one must not be underlined and must have for hint: my name. (Force the students to do an internet search to find the attribute of the EditTextView to modify)

<details>
  <summary> Click for Solution: Lab solutions </summary>

- Link to the [lab solution](https://gist.github.com/ironhack-edu/c3e7fba417de11bcf152ba6329acbbb4).

</details>

---
### :book: Bibliography
- [Layout graphical tool editor](https://developer.android.com/studio/write/layout-editor)
- [Official layout documentation](https://developer.android.com/guide/topics/ui/declaring-layout)
- [Layout attributes explanation](https://medium.com/androiddevelopers/layouts-attributes-and-you-9e5a4b4fe32c)

---
### What's next?
- Focus on constraint layout
- Advanced explanation of the constraint system
- Introduction to the responsive concept
