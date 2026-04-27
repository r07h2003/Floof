
# 🐾 Floof — Pet Health Tracker
> *Your pet can't tell you how they feel. Floof can.*

![Status](https://img.shields.io/badge/Status-In%20Development-purple)
![Platform](https://img.shields.io/badge/Platform-iOS-blue)
![Built With](https://img.shields.io/badge/Built%20With-Claude%20AI-orange)

<img width="382" height="883" alt="Screenshot 2026-04-27 at 2 00 24 PM" src="https://github.com/user-attachments/assets/8f3e43a3-5a97-4a23-962a-5a0ea2e045fa" />
---

## The Problem

There are apps that help new parents track every feeding, every sleep cycle, and every health signal of their newborn. But nothing equivalent exists for pet owners, who face the exact same anxiety, with none of the same support.

Pets are a different species, their signals are subtle. Whether you're a first time pet owner figuring things out, or someone who has had a dog for years, the uncertainty never fully goes away:

> *"Am I missing something? Is this normal? Should I be worried?"* are the questions pet parents are always asking themseleves 

I noticed this gap after coming across a baby tracking app and asking myself, why doesn't this exist for pets? Pet owners love their animals just as deeply, but have far fewer tools to understand what's happening with their health day to day.

That question became Floof.

---

## What Floof Does

Floof tracks the four core pillars of pet health — **sleep, feeding, activity, and bathroom habits** and runs them through an AI health scoring system that:

- 🚨 **Flags** when something looks off
- 📊 **Summarizes** your pet's overall wellness patterns over 7 days, 30 days, and 3 months
- 🎯 **Personalizes** goals based on your pet's species, breed, age, and size
- 📅 **Builds routines** so pet parents know exactly what's happening and when

---

## App Screens & Features

### Onboarding
A clean 8-step onboarding flow that customizes everything around your pet. Users select their pet's species (Dog, Cat, Rabbit, Bird, Small Animal), name, breed, age, size, and primary health goal. Age-based tips are surfaced inline - for example, notifying new puppy owners that puppies sleep up to 18–20 hours a day.

<img width="382" height="883" alt="Screenshot 2026-04-27 at 2 05 00 PM" src="https://github.com/user-attachments/assets/ee289b66-4897-4b9c-a58f-ec67a0bbb168" /> <img width="382" height="883" alt="Screenshot 2026-04-27 at 2 04 41 PM" src="https://github.com/user-attachments/assets/4414ea9d-b833-43e2-a82b-5d073683e08f" /> <img width="382" height="883" alt="Screenshot 2026-04-27 at 2 05 21 PM" src="https://github.com/user-attachments/assets/79763d1e-7a4e-4ccb-990b-11549e9ec394" />



### Home Dashboard
The home screen shows an at-a-glance view of your pet's day — active events, today's journal entries, AI powered Floof Insights, and goal completion status. A quick log bar lets you log Sleep, Wake, Feed, Play, and Bathroom events in one tap.

### Log
Four tracking categories — Sleep, Feed, Bathroom, and Activity. The sleep logger includes a live timer, sleep quality rating (paw print scale), location tagging (Home bed, Crate, Couch, Your bed), and optional notes.

### Routine
A daily routine view showing all scheduled events in chronological order with completion status. Includes a Timeline toggle for a visual overview. At a glance stats show sleep goal, wake window, and total events logged.

### Wellness Insights (Stats)
The core AI feature. A health score (0–100) with a status label — Great, Good, Needs Attention — broken down by Sleep, Feeding, and Activity. Includes a sleep pattern chart over time and feeding consistency percentage. Viewable across 7 days, 30 days, and 3 months.

### Pet Profile
Full pet profile including breed, age, weight, sex, health conditions, allergies, and vaccination records with status indicators (Up to date / Due soon / Overdue). Vet information is stored including clinic name and phone number.

### More
Multi pet support, caregiver sharing (share access with family or vets), calming sounds toggle, and rest window reminder notifications.

---

## My Role

I built Floof as the sole founder with no coding background. Every product decision — the problem to solve, the features to build, what to cut, how to onboard users, how to frame the AI insights, was mine. I used Claude AI as a vibe coding partner to handle the technical implementation.

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
- What they currently tracked (mostly nothing, all in their heads)
- What would make them trust and use an app like this

The consistent answer across everyone I spoke to:

> *"I just want to know if something is wrong before it becomes a vet visit."*

That single insight shaped the entire product - the health score, the flagging system, and the calm, low-anxiety design language throughout.

---

## Key Product Decisions

**Why personalize by species and age?**
A 8-week-old puppy has completely different health needs than a 7-year-old cat. Generic tracking doesn't work, everything needs to be calibrated to the animal. This is why onboarding collects species, breed, age, and size before showing any goals or benchmarks.

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

## Insight

The baby tracking app market is mature and crowded. The pet health tracking space is not, despite pet ownership being at an all time high and pet parents spending more than ever on their animals.

Floof is built on the bet that pet parents deserve the same quality of health intelligence that new human parents already have.

---

*Built by Rohan | Portfolio Project*
