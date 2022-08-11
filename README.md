# Thockit

Thockit is a Reddit clone themed around mechanical keyboards.

[View live here!](https://thockit.vercel.app/)

All photos used belong to their respective owners, and were used solely for educational purposes only.

![Thockit](public/Thockit_page.png?raw=true)

## Purpose

I created this project following a tutorial based on my interest in custom mechanical keyboards. At the beginning of my custom keyboard journey, I would often find myself on Reddit reading posts and comments to gain more knowledge regarding everything related to custom mechanical keyboards. I would often browse the r/MechanicalKeyboards subreddit or keep up to date with the latest products in r/MechGroupBuys. So I thought it would be a great project idea to recreate Reddit and its core functionality.

## Details

The technologies used to make this website are React v18.1 with Typescript, Next.js 12.1.0, Tailwind CSS v3.1.2, Supabase, and Stepzen. This was my first full stack project, where I utilized Next.js and Tailwind CSS for the frontend while Supabase and Stepzen handled the backend. I also utilized some packages such as react-hook-form, react-hot-toast, and react-timeago to help with some of the functionality of the website as well as some aesthetic packages such as heroicons. 

I also utilized NextAUTH to allow users to sign into the app with their real Reddit account securely. Supabase is essentially a Firebase alternative where I have my data stored and Stepzen is used to easily generate GraphQL Schemas and APIs for my data. The core functionality of this Reddit app include creating posts (as well as new subreddits), typing comments, and upvoting/downvoting posts. The icons in the header do not work at the moment and are purely there for aesthetics.

## Project Status

This project at its core is essentially complete. The focus was only on the core functions of Reddit which is to make posts in subreddits (and create new subreddits), comment on them, and upvote/downvote posts. 
