# MindMarshal Audio Sanctuary
### *A Massive, Ever‑Expanding Audio Library for Calm, Focus, and Emotional Regulation*

The **MindMarshal Audio Sanctuary** is the official audio library powering the Calm Tools suite inside the **MindMarshal Task Coach** app.  
This repository hosts a growing collection of high‑quality, royalty‑free audio tracks designed to support:

- ADHD focus  
- Emotional regulation  
- Grounding  
- Meditation  
- Deep work  
- Sleep  
- Stress reduction  
- Sensory soothing  

The library integrates directly with the MindMarshal app through a dynamic remote loader, allowing new audio tracks to appear instantly for users without requiring an app update.

---

## 🎧 What This Repository Contains

This repo includes a structured, scalable audio library organized into the following categories:

### **White Noise**
- Pure white noise  
- Brown noise  
- Pink noise  
- Fan hum  
- Static blends  
- Low‑frequency focus tones  

### **Nature Sounds**
- Rain (light, medium, storm)  
- Ocean waves  
- Forest ambience  
- Waterfalls  
- Fireplace crackle  
- Wind and desert ambience  

### **Theta & Binaural Waves**
- 4 Hz theta  
- 6 Hz theta  
- 8 Hz theta  
- Deep meditation tones  
- Binaural focus blends  

### **Calming Music**
- Soft piano  
- Ambient pads  
- Gentle guitar  
- Meditation bells  
- Slow synth waves  

### **Focus Pads**
- Long‑form ambient pads  
- Deep work textures  
- Minimalist soundscapes  

Each category is designed to support different emotional and cognitive states, giving MindMarshal users a wide range of sensory tools.

---

## 📁 Repository Structure
mindmarshal-audio/
│
├── audio/
│   ├── white-noise/
│   ├── nature/
│   ├── theta/
│   ├── calming-music/
│   └── focus-pads/
│
└── tracks.json

- **audio/** contains all hosted audio files  
- **tracks.json** is the master catalog the app loads dynamically  

This structure allows the MindMarshal app to fetch and display hundreds of tracks instantly.

---

## 🌐 Dynamic Remote Loading (How the App Uses This Repo)

The MindMarshal app fetches:
https://JEBenterprise247-Revive.github.io/mindmarshal-audio/tracks.json (JEBenterprise247-Revive
.github.io in Bing)

This JSON file defines:
- Categories  
- Track titles  
- Descriptions  
- File URLs  
- Metadata  

The app merges this remote library with its local fallback audio, ensuring:
- Instant updates  
- Infinite expansion  
- Zero app store resubmissions  

You can add new tracks anytime by:
1. Uploading the audio file  
2. Adding an entry to `tracks.json`  

Users will see the new audio immediately.

---

## 📤 User‑Uploaded Audio Support

MindMarshal also allows users to upload their own audio files directly from their device.  
This repo does **not** store user uploads — they remain private on the user’s device.

This repository provides:
- The global library  
- The structure  
- The metadata  
- The streaming endpoints  

User uploads are handled locally inside the app.

---

## 🔒 Licensing & Safety

All audio hosted in this repository must be:
- Royalty‑free  
- Licensed for redistribution  
- Safe for public use  
- Non‑copyrighted  
- Not containing speech, lyrics, or identifiable content unless owned by the repository owner  

This ensures:
- Legal safety  
- App store compliance  
- User trust  

---

## 🚀 Contributing & Expanding the Library

You can expand the library anytime by:
1. Adding new audio files to the appropriate folder  
2. Updating `tracks.json` with:
   - `id`
   - `title`
   - `description`
   - `url`

The MindMarshal app will automatically detect and display new tracks.

---

## 📱 About MindMarshal

MindMarshal is a premium ADHD‑friendly task coach and emotional regulation system designed to help users:

- Break down tasks  
- Manage overwhelm  
- Build routines  
- Regulate emotions  
- Improve focus  
- Reduce stress  
- Stay grounded  

The Audio Sanctuary is a core part of the Calm Tools experience, providing sensory support for users during moments of stress, distraction, or emotional overload.

---

## 💬 Support

For issues, suggestions, or audio requests, please open an Issue in this repository.
