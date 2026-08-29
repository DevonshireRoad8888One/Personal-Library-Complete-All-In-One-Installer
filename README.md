# Personal-Library-Complete-All-In-One-Installer
Personal Library — Complete All-In-One Installer
🎯 How To Use On Second Laptop
bash

Collapse
Save
Copy
1
2
3
4
5
6
7
8
9
10
11
# 1. Copy the entire script above to second laptop
# (or paste directly into terminal)

# 2. Run the installer
~/install-personal-library-complete.sh

# 3. Check health
~/library-manager/health-all.sh

# 4. Open browser
firefox http://localhost:8771
📋 To Sync With First Laptop
After install on Laptop B, match the comm code:

bash

Collapse
Save
Copy
1
2
3
4
5
6
7
8
9
# On Laptop A (first one):
cat ~/library/.env | grep LIBRARY_COMM_CODE

# On Laptop B (second one):
nano ~/library/.env
# Change LIBRARY_COMM_CODE to match Laptop A
# Restart:
~/library-manager/stop-all.sh
~/library-manager/start-all.sh
✅ This Installer Includes
✅ All models (items, tags, item_tags, sources, base)
✅ Database with migration support
✅ FastAPI server on port 8771
✅ Mesh discovery on port 8772
✅ Video/image/audio inline playback
✅ PDF download support
✅ JSON content display
✅ Drag-drop upload
✅ Timestamp chain
✅ Content hash dedup
✅ Management scripts (start/stop/health)
Run it and your second laptop will have everything! 🚀
