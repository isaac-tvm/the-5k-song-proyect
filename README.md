Spotify Big Data Insights:
A deep-dive analysis into the Spotify Million Playlist Dataset, exploring the relationship between track popularity, tempo (BPM), and musical theory patterns.

Overview
This project processes over 12 million rows of Spotify user data to identify what makes a song "sticky." By integrating external musical metadata, we analyzed the Top 20 most frequent tracks to find the "Sweet Spot" of success.

Tech Stack
Language: Python 3.13

Data Manipulation: Pandas (Chunk-based processing for Big Data)

Visualization: Seaborn, Matplotlib

API Integration: Spotipy (Spotify Web API)

Musical Analysis: Data Enrichment via Manual & Automated Mapping

📈 Key Findings
1. Musical DNA Breakdown: The Science of the Top 20
This is precisely what elevates a Data Science project from a simple spreadsheet to a legitimate market study. I'm decoding the "success formula" behind the last decade of Pop and Indie hits.

The data confirms it: the 100–130 BPM range is the "human heartbeat" of movement and emotion—matching the rhythm of a brisk walk or an energetic dance.

2. Harmonic Dominance
The dataset shows one progression reigning supreme. It is the industry’s "Gold Standard":

The "Epic" Progression (vi - IV - I - V): This sequence (and variations like I - V - vi - IV) is present in almost every top-tier track.

Examples in your list: Radioactive, Wake Me Up, Counting Stars, Let Her Go, Somebody That I Used To Know.

Why it works: It creates an "infinite loop" sensation. It isn't purely sad or overly happy; it feels evocative and driving.

The Minor-Key Hook: Tracks like Midnight City and Do I Wanna Know? utilize a minimalist, minor-degree structure to deliver that "nocturnal" or "mysterious" vibe that defined the modern Indie era.

3. Lyric Sentiment
Based on the Top 20 tracks, the lyrics fall into three primary "buckets":

Nostalgia & Identity (40%): The strongest theme. It’s not "toxic heartbreak"; it’s a search for self or "remembering better times."

Midnight City, Royals, Pumped Up Kicks, We Are Young, Smells Like Teen Spirit.

Resilience & Empowerment (30%): "Unstoppable" anthems or "rebirth" narratives.

Radioactive, Can't Hold Us, Wake Me Up, Counting Stars.

Artful Heartbreak (30%): The classic breakup song, but with a sophisticated, artistic twist.

Somebody That I Used To Know, Let Her Go, Sweet Disposition.


Big Data Handling: Processed 12M+ records using chunksize to optimize memory on local hardware.

Fuzzy Matching: Cleaned track and artist names using Regex to ensure high-accuracy merges between the main dataset and musical metadata.

Canción          BPM           Progresión                     Lyrics
Radioactive	     136	      vi-IV-I-V (Am-F-C-G)	  Empowerment / Resilience
Wake Me Up	     124	      vi-IV-I-V (Am-F-C-G)	    Search for Identity
Royals           85	         I-bVII-IV (D-C-G)	     Social Critique / Identity
Get Lucky	       116	      vi-I-III-V (Bm-D-F#m-E)	  Connection / Celebration
Counting Stars	 122	       vi-I-V-IV (Am-C-G-F)	        Ambition / Life


Visualizations

<img width="800" height="600" alt="Figure_1" src="https://github.com/user-attachments/assets/90cbaee9-6e4f-4fd6-bd4f-43e2dcbf5aba" />

Conclusions:

The Homogeneity of Success": We observe a high correlation between Tempo (avg. 120 BPM) and Harmonic Structure (vi-IV-I-V). The most frequent tracks in global playlists are rarely the most musically complex; instead, they utilize rhythmic frequencies aligned with human gait and lyrical structures rooted in collective nostalgia.


As a musician, this project started with a practical question: Can data help us write a 'Steady earner' rather than a 'fading hit'? Instead of chasing a million-dollar unicorn, I aimed to reverse-engineer the characteristics of songs that generate consistent, linear income—specifically targeting a goal of $5,000 MXN/week ($250 USD). To achieve the ~11,000 daily streams required for this, I analyzed how songs successfully penetrate 'Niche Playlists'. This repository is my technical roadmap to understanding the tempo, structure, and recurring patterns that keep a track alive in the ears (and playlists) of listeners worldwide
