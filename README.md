## Running
```bash
git clone https://github.com/d1scocat/Tritonchikapp.git
cd Tritonchikapp
npm install
npm run start
```

## Notes
if you use any proxy or other network redirecting application on your device, it might interfere with the internal Vite <-> Electron bridge

## API
this app is useless without an api, access it at the respective repository (do this in a different repository):
```bash
git clone https://github.com/ecxqua/Tritonchikeee.git
cd Tritonchikeee
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
uvicorn api.entrypoint:app --port 3002
```