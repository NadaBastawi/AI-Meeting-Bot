# AI Meeting Bot

## Inspiration

Our main inspiration for this project is the time-consuming task of creating Meeting Minutes by hand after every virtual meeting. As college students who are part of several student chapters, we felt that there is a serious need to automate this tedious yet crucial job, and we realised the potential AI can bring into this field. Thus MeetMate was born, the perfect AI companion for all your meeting summarisation tasks.

## What it does

MeetMate is an AI-powered virtual meeting assistant that lets users quickly generate detailed summaries and documents about their meetings. Just upload the meeting recording, and along with the meeting Minutes, MeetMate also provides a full audio transcript and automatically schedules follow-up meetings in the user's Google Calendar.

## How we built it

We built MeetMate in Python and utilised Microsoft's Azure AI Foundry, Azure Speech Services, and their supporting SDK packages. We built the audio transcription and diarization with Azure AI Speech's Fast Transcription REST API and used OpenAI's GPT-4o for Minutes generation and document creation. MeetMate also uses the Google Cloud Platform (GCP) to access the Google Calendar API for automated event scheduling. All this sweet functionality is under the hood of a slick webpage UI built using HTML5, CSS and Flask. During the entire dev cycle, we used GitHub Copilot as our AI pair programmer to speed up the coding phase, generate code snippets, and fix bugs.

## Built With

AI, Azure-AI, CSS3, Javascript, HTML5, Github-Copilot, Openai, Python, Redis, Azure Speech-to-text
