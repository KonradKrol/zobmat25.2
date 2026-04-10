# zobmat25.2

zobmat25.2 is a web project created for the AGH competition **"Zobaczyć Matematykę" (2024–2025 edition)**.

The website focuses on probability distributions. It helps users understand them by showing visual charts, formulas, and interactive tools based on user input.

Main competition website: https://www.zobaczycmatematyke.agh.edu.pl

## Live demo

https://d2vr1dj8lr3noc.cloudfront.net/

## What it does
- Lets you try out different probability distributions  
- Shows charts based on parameters you enter  
- Displays formulas and simple explanations  
- Allows you to pick out random numbers from distributions  
- Calculates probability that a value falls into a given range  

## Features
- Modern, clean UI (dashboard style)  
- Accessibility mode  
- Multiple themes  
- Interactive charts (built with `fl_chart`)  
- State management with `bloc`  
- Math rendering using `flutter_math_fork`  
- Some UI parts were put together with help from AI  

## Tech stack
- Flutter Web (fully)  
- Hosted on Amazon CloudFront + Amazon S3 
- Key libraries:
  - fl_chart  
  - bloc  
  - flex_color_scheme  
  - flutter_math_fork  
  - hyper_link  
  - equatable  
  - shared_preferences  

## Project structure

Source code is located in the `lib` folder.

## Screenshots
<img width="2247" height="1344" src="https://github.com/user-attachments/assets/7456df55-9753-4c22-a5cd-6789f21911fb" />
<img width="2247" height="1344" src="https://github.com/user-attachments/assets/256317ce-7122-4cb1-9d16-5303edf51196" />
<img width="2247" height="1344" src="https://github.com/user-attachments/assets/d192812f-afd6-43e8-9ad0-d94e73fd5adf" />
<img width="2247" height="1344" src="https://github.com/user-attachments/assets/1855966c-012d-48b1-8087-b9e1b1bb330e" />
<img width="2247" height="1344" src="https://github.com/user-attachments/assets/4809e23a-7d07-4ba5-b480-95f7bb408618" />
