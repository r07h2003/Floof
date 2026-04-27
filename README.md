# 🐾 Floof — Pet Health Tracker

> *Your pet can't tell you how they feel. Floof can.*

![Status](https://img.shields.io/badge/Status-In%20Development-purple)
![Platform](https://img.shields.io/badge/Platform-iOS-blue)
![Built With](https://img.shields.io/badge/Built%20With-Claude%20AI-orange)

---

<div align="center">
  <img src="https://github.com/user-attachments/assets/8f3e43a3-5a97-4a23-962a-5a0ea2e045fa" width="220"/>
</div>

---

## The Problem

There are apps that help new parents track every feeding, every sleep cycle, and every health signal of their newborn. But nothing equivalent exists for pet owners — who face the exact same anxiety, with none of the same support.

Pets are a different species. Their signals are subtle. Whether you're a first-time pet owner figuring things out, or someone who has had a dog for years, the uncertainty never fully goes away:

> *"Am I missing something? Is this normal? Should I be worried?"*

I noticed this gap after coming across a baby tracking app and asking myself — why doesn't this exist for pets? Pet owners love their animals just as deeply, but have far fewer tools to understand what's happening with their health day to day.

That question became Floof.

---

## What Floof Does

Floof tracks the four core pillars of pet health — **sleep, feeding, activity, and bathroom habits** — and runs them through an AI health scoring system that:

- 🚨 **Flags** when something looks off
- 📊 **Summarizes** your pet's overall wellness patterns over 7 days, 30 days, and 3 months
- 🎯 **Personalizes** goals based on your pet's species, breed, age, and size
- 📅 **Builds routines** so pet parents know exactly what's happening and when

---

## App Screens & Features

### Onboarding

A clean 8-step onboarding flow that customizes everything around your pet. Users select their pet's species, name, breed, age, size, and primary health goal. Age-based tips are surfaced inline — for example, notifying new puppy owners that puppies sleep up to 18–20 hours a day.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/a7fd82f5-a12a-4f37-baa0-a87977b7cf4c" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/2b641a07-2fd5-435b-a17d-2a2426cde5e4" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/4bed299b-fc1d-4c1f-b6db-567f6c6498f3" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/87ab7da5-f49f-458d-91f0-e4d325bf56ff" width="200"/></td>
  </tr>
  <tr>
    <td align="center">Pet Type Selection</td>
    <td align="center">Age Setup</td>
    <td align="center">Goal Selection</td>
    <td align="center">Personalized Plan</td>
  </tr>
</table>

---

### Home Dashboard

The home screen shows an at-a-glance view of your pet's day — active events, today's journal entries, AI-powered Floof Insights, and goal completion status. A quick log bar lets you log Sleep, Wake, Feed, Play, and Bathroom events in one tap.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/ce28c28f-c145-46f8-97f5-bf7b49f59c57" width="200"/></td>
  </tr>
</table>

---

### Log

Four tracking categories — Sleep, Feed, Bathroom, and Activity. The sleep logger includes a live timer, sleep quality rating (paw print scale), location tagging (Home bed, Crate, Couch, Your bed), and optional notes.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/e2db6d07-cd6f-4ddf-9104-57b3ee27fc6a" width="200"/></td>
  </tr>
</table>

---

### Routine

A daily routine view showing all scheduled events in chronological order with completion status. Includes a Timeline toggle for a visual overview. At-a-glance stats show sleep goal, wake window, and total events logged.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/90e40fa7-7aa3-433a-8b42-5c1bf9d964b3" width="200"/></td>
  </tr>
</table>

---

### Wellness Insights (Stats)

The core AI feature. A health score (0–100) with a status label — Great, Good, Needs Attention — broken down by Sleep, Feeding, and Activity. Includes a sleep pattern chart over time and feeding consistency percentage. Viewable across 7 days, 30 days, and 3 months.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/0cbdaaa0-ce37-4c38-b55a-eb3459eea72a" width="200"/></td>
  </tr>
</table>

---

### Pet Profile

Full pet profile including breed, age, weight, sex, health conditions, allergies, and vaccination records with status indicators (Up to date / Due soon / Overdue). Vet information is stored including clinic name and phone number.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/e186d6a6-58cf-43fd-8fd2-f0305e4e7bc9" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/eaa92007-4812-413a-8f1c-647d5aebf40c" width="200"/></td>
  </tr>
  <tr>
    <td align="center">Pet Details</td>
    <td align="center">Vaccinations & Vet Info</td>
  </tr>
</table>

---

### More

Multi-pet support, caregiver sharing (share access with family or vets), calming sounds toggle, and rest window reminder notifications.

---

## My Role

I built Floof as the sole founder with no coding background. Every product decision — the problem to solve, the features to build, what to cut, how to onboard users, how to frame the AI insights — was mine. I used Claude AI as a vibe coding partner to handle the technical implementation.

This mirrors exactly how PMs work with engineering teams: you define the problem worth solving, make the product calls, and collaborate with others to bring it to life.

**What I owned:**
- Product vision and problem framing
- User research (conversations with pet-owning friends and families)
- Feature prioritization — what makes it into v1 vs. later
- Onboarding flow design and copy
- AI health scoring concept and how insights are surfaced
- Overall UX structure and navigation

---

## User Research

Before building, I spoke with friends who own pets and their families. I wanted to understand:

- What worried them most about their pet's health day to day
- What they currently tracked (mostly nothing — all in their heads)
- What would make them trust and use an app like this

The consistent answer across everyone I spoke to:

> *"I just want to know if something is wrong before it becomes a vet visit."*

That single insight shaped the entire product — the health score, the flagging system, and the calm, low-anxiety design language throughout.

---

## Key Product Decisions

**Why personalize by species and age?**
An 8-week-old puppy has completely different health needs than a 7-year-old cat. Generic tracking doesn't work — everything needs to be calibrated to the animal. This is why onboarding collects species, breed, age, and size before showing any goals or benchmarks.

**Why a health score instead of raw data?**
Pet owners are not vets. Showing raw numbers — "your dog slept 14.5 hours" — means nothing without context. A score of 100 with "Thriving!" is immediately understandable. The data lives underneath for those who want it.

**Why include caregivers?**
Pets often have multiple people caring for them — partners, family members, dog walkers, vets. Tracking only works if the full picture is captured. Caregiver sharing ensures no event gets missed regardless of who is with the pet.

**Why calming sounds?**
A small but intentional feature. Anxious pets and anxious pet parents both benefit from a calm environment. It reinforces the brand — Floof is not a clinical health tool, it's a gentle companion app.

---

## What's Next

- [ ] Push notifications for missed routine events
- [ ] Vet appointment booking integration
- [ ] Weight tracking over time
- [ ] Multi-pet household dashboard
- [ ] App Store launch

---

## Built With

- Claude AI (vibe coding partner)
- iOS
- AI health scoring engine

---

## The PM Insight

The baby tracking app market is mature and crowded. The pet health tracking space is not — despite pet ownership being at an all-time high and pet parents spending more than ever on their animals.

Floof is built on the bet that pet parents deserve the same quality of health intelligence that new human parents already have.

---

*Built by Rohan | Product Management Portfolio Project*
