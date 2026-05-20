# VibeCare

A platform that connects families with elderly dependents to 
verified live-in caregivers in Portugal.

Built as an MVP for a vibe coding course final project, using 
Google Antigravity and Firebase.

---

## What it does

- Families register their elderly relative's profile and care needs
- Caregivers register their experience and availability
- An admin dashboard allows manual matching between families 
  and caregivers

---

## Tech Stack

- **Frontend:** React
- **Auth & Database:** Firebase (Authentication + Firestore)
- **Builder:** Google Antigravity (Gemini 3)
- **Deployment:** Firebase Hosting

---

## Pages

| Route | Description |
|---|---|
| `/` | Landing page |
| `/family` | Family signup and profile form |
| `/caregiver` | Caregiver signup and profile form |
| `/admin` | Password-protected admin dashboard |

---

## How to run locally

1. Clone the repository
2. Install dependencies: `npm install`
3. Add your Firebase config to `.env`
4. Start the app: `npm run dev`

---

## Admin Access

URL: `/admin`  
Password: `vibecare2025`

---

## Project context

VibeCare started as a real business concept — a local elder 
care agency in Leiria, Portugal. This MVP validates the core 
user flows before investing in full product development.

The business model: families pay a one-time matching fee 
(€300–500) and a monthly management subscription (€80–120) 
in exchange for a verified caregiver, legal contract support, 
and guaranteed substitution during holidays.

---

## Next steps (post-MVP)

- [ ] AI matching feature (suggest best caregiver per family)
- [ ] In-app messaging between families and caregivers
- [ ] Caregiver background check integration
- [ ] Email notifications on new registrations
- [ ] Mobile-responsive polish

---

## Author

Built by Carolina — Leiria, Portugal  
Course: AI Vibe Coding  
Year: 2025