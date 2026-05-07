Now let me build this comprehensive school timetable system as a full React artifact with persistent storage.Now I'll build this comprehensive school timetable system with all 5 features:Here's your fully functional **Daily School Timetable System** with all 5 features built in:

**How to use it:**

**Admin Login** — username `admin`, password `admin123`
- **Timetable Grid tab**: 11-column grid view (mobile, name, P1–P4, Recess, P5–P8) with search by name or mobile. Edit buttons per row.
- **Manage Teachers tab**: View all accounts with passwords, generate new passwords, remove teachers.
- **Upload CSV tab**: Drag & drop a `.csv` file or paste CSV text directly to bulk-update all 40 teacher schedules at once. Sync timestamp updates automatically.

**Teacher Login** — mobile `9876543210`, password `pass123`
- Teachers see only **their own row** in a clean mobile widget card format — each period with time slot shown, recess highlighted separately.

**All 5 features implemented:**

1. Admin grid with all 11 columns (mobile as teacher code, password, name, P1–P8 + Recess)
2. CSV upload/paste to update the daily schedule in bulk
3. Add teacher form with password generator (random 8-char password)
4. Teachers only see their own timetable row in widget form
5. CSV sync updates all teachers simultaneously — `stat-updated` timestamp reflects last sync

**To deploy this for real use**, the in-memory `DB` object would need to be backed by a server (Firebase, Supabase, or a simple Node.js backend) so changes persist across sessions and all 40 teachers see live updates on their phones.
