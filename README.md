# File Manager
This project is a work-in-progress. 

A program to easily share a directory. Generates previews for media files. Files can be sorted. Supports common hotkeys in media viewer.

## Frontend
### Tools used
- TypeScript
- React 
- ReactRouterDOM
- Redux
- RTK Query
- Vite

### Description
One of my first projects when I started learning webdev. This project involved writing a small [component library](https://github.com/arinode/filemanager_frontend/tree/main/src/components) for React, designing a [basic api](rest.md), interacting with it using RTK Query, and implementing navigation using React Router DOM, as well as designing UI with HTML/CSS.

## Backend
- Node.js
- Express.js
- FFmpeg

### Descripiton
Not much to say. Receive the request, resolve path, verify that the resolved path is not outside the allowed directory, spawn ffmpeg or return readdir(), return JSON.
