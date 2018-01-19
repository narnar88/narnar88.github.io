---
layout: project
type: project
title: final-project
permalink: projects/final-project
# All dates must be YYYY-MM-DD format!
date: 2017-12-05
labels:
  - C++
  - Inheritance
  - Polymorphism
summary: A command line C++ program developed in ICS 212
---

Final Project Documentation

Introduction

   This is program is a command line program written in C++. This program mimics a database of student and staff information for a college. The program displays the name, campus, student ID, and major for student objects, and name, campus, staff ID, and department for staff objects. The main goal of this program was to implement inheritance and polymorphism, which was accomplished by creating objects, and utilizing inheritance operators and set() and get() methods.
   
How to Run the Application

   The display begins with requesting a student’s information. The user is prompted for the name first, followed by campus, student ID, and major. The program then returns the information inputted. Next, the user is prompted for staff information. The user is prompted for the name first, followed by campus, staff ID, and then department. The program then returns the information inputted for the staff.
   
Sample from Runtime

Naryssas-MacBook-Pro:ICS212F17 naryssa$ ./finalproject

Please input the NAME of the student: Moana of Motunui

Student's CAMPUS: UH Manoa

Student's ID: 13942

Student's MAJOR: ICS

Name: Moana of Motunui

Campus: UH Manoa

Student ID: 13942

Major: ICS

Please input the NAME of the staff:

Maui the Demigod

Staff's CAMPUS: KCC

Staff's ID: 65241

Staff's DEPARTMENT: Anthropology

Name: Maui the Demigod

Campus: KCC

Staff ID: 65241

Department: Anthropology


