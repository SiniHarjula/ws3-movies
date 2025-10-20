WS3 – OMDb Movies

Clone and run:
1. `git clone https://github.com/SiniHarjula/WS3.git`
2. `cd WS3`
3. `npm install`
4. Get your OMDb API key: https://www.omdbapi.com/apikey.aspx
5. Start locally:
   - Windows: `$env:OMDB_API_KEY="YOUR_KEY"; npm start`
   - macOS/Linux: `export OMDB_API_KEY="YOUR_KEY" && npm start`
7. Open **http://localhost:5000/** — the `/` page shows the movie table.

API key:
- Don’t upload your key to GitHub (.env is in .gitignore).
- On Render, add Environment Variable: `OMDB_API_KEY = your key`.   
