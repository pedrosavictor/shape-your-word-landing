# Christmas Ornaments Workshop - Email Sequences

## SEQUENCE 1: Sunday, December 21st (2:00 PM UK)

---

### Email 1: Confirmation (Send immediately)

**Subject:** You're in! Here's your workshop link for Sunday

**Body:**

Hey {{ subscriber.first_name }},

You're all set for the Christmas Ornaments Workshop!

**Here are your details:**

- **Date:** Sunday, December 21st
- **Time:** 2:00 PM UK time
- **Duration:** 90 minutes
- **Where:** Online via Google Meet

**Your workshop link:**
[PLACEHOLDER: INSERT GOOGLE MEET LINK FOR DEC 21]

Save this link somewhere safe - you'll need it on Sunday.

I'll send you a materials checklist in my next email so you have everything ready.

See you soon,
Victor

P.S. Add this to your calendar so you don't forget!

---

### Email 2: Materials Checklist (Send 1 day after signup)

**Subject:** What you'll need for Sunday's workshop

**Body:**

Hey {{ subscriber.first_name }},

Quick reminder - our workshop is coming up on Sunday at 2:00 PM UK.

Here's everything you'll need:

**Essential materials:**

- **Air dry clay** (about 1kg) - [PLACEHOLDER: AMAZON LINK]
  I recommend Scola air dry clay

- **Rolling pin** - or a wine bottle works great
  [PLACEHOLDER: AMAZON LINK IF NEEDED]

- **Cookie cutters or knife** - for cutting shapes
  [PLACEHOLDER: AMAZON LINK IF NEEDED]

- **Skewer or straw** - for making hanging holes

- **Small bowl of water** - for smoothing

- **Baking paper** - or any clean, non-stick surface

**That's it!** No kiln, no pottery wheel, no special studio. Just your table.

[PLACEHOLDER: LINK TO AMAZON STOREFRONT]
I've put together an Amazon storefront with all my recommendations if you want to grab everything in one go.

**Your workshop link (save this!):**
[PLACEHOLDER: INSERT GOOGLE MEET LINK FOR DEC 21]

See you Sunday!
Victor

---

### Email 3: Reminder (Send on December 20th - 1 day before)

**Subject:** Tomorrow! Christmas Ornaments Workshop at 2pm

**Body:**

Hey {{ subscriber.first_name }},

Just a friendly reminder - we're making Christmas ornaments together tomorrow!

**Workshop details:**
- **When:** Sunday, December 21st at 2:00 PM UK
- **Link:** [PLACEHOLDER: INSERT GOOGLE MEET LINK FOR DEC 21]

**Quick checklist:**
- [ ] Air dry clay ready
- [ ] Rolling pin (or wine bottle)
- [ ] Cookie cutters or knife
- [ ] Skewer or straw
- [ ] Small bowl of water
- [ ] Baking paper or clean surface

Find a spot at your table, get your materials out, and I'll see you tomorrow.

This is going to be fun.

Victor

---

### Email 4: Day-of reminder (Send on December 21st morning)

**Subject:** See you in a few hours!

**Body:**

Hey {{ subscriber.first_name }},

Today's the day! Our workshop starts at 2:00 PM UK.

**Click here to join:** [PLACEHOLDER: INSERT GOOGLE MEET LINK FOR DEC 21]

I'd suggest joining 5 minutes early so you're all set up when we begin.

Get your clay and materials ready, find a comfortable spot, and let's make something beautiful together.

See you soon,
Victor

---
---

## SEQUENCE 2: Monday, December 22nd (7:00 PM UK)

---

### Email 1: Confirmation (Send immediately)

**Subject:** You're in! Here's your workshop link for Monday

**Body:**

Hey {{ subscriber.first_name }},

You're all set for the Christmas Ornaments Workshop!

**Here are your details:**

- **Date:** Monday, December 22nd
- **Time:** 7:00 PM UK time
- **Duration:** 90 minutes
- **Where:** Online via Google Meet

**Your workshop link:**
[PLACEHOLDER: INSERT GOOGLE MEET LINK FOR DEC 22]

Save this link somewhere safe - you'll need it on Monday.

I'll send you a materials checklist in my next email so you have everything ready.

See you soon,
Victor

P.S. Add this to your calendar so you don't forget!

---

### Email 2: Materials Checklist (Send 1 day after signup)

**Subject:** What you'll need for Monday's workshop

**Body:**

Hey {{ subscriber.first_name }},

Quick reminder - our workshop is coming up on Monday at 7:00 PM UK.

Here's everything you'll need:

**Essential materials:**

- **Air dry clay** (about 1kg) - [PLACEHOLDER: AMAZON LINK]
  I recommend Scola air dry clay

- **Rolling pin** - or a wine bottle works great
  [PLACEHOLDER: AMAZON LINK IF NEEDED]

- **Cookie cutters or knife** - for cutting shapes
  [PLACEHOLDER: AMAZON LINK IF NEEDED]

- **Skewer or straw** - for making hanging holes

- **Small bowl of water** - for smoothing

- **Baking paper** - or any clean, non-stick surface

**That's it!** No kiln, no pottery wheel, no special studio. Just your table.

[PLACEHOLDER: LINK TO AMAZON STOREFRONT]
I've put together an Amazon storefront with all my recommendations if you want to grab everything in one go.

**Your workshop link (save this!):**
[PLACEHOLDER: INSERT GOOGLE MEET LINK FOR DEC 22]

See you Monday!
Victor

---

### Email 3: Reminder (Send on December 21st - 1 day before)

**Subject:** Tomorrow! Christmas Ornaments Workshop at 7pm

**Body:**

Hey {{ subscriber.first_name }},

Just a friendly reminder - we're making Christmas ornaments together tomorrow evening!

**Workshop details:**
- **When:** Monday, December 22nd at 7:00 PM UK
- **Link:** [PLACEHOLDER: INSERT GOOGLE MEET LINK FOR DEC 22]

**Quick checklist:**
- [ ] Air dry clay ready
- [ ] Rolling pin (or wine bottle)
- [ ] Cookie cutters or knife
- [ ] Skewer or straw
- [ ] Small bowl of water
- [ ] Baking paper or clean surface

Find a spot at your table, get your materials out, and I'll see you tomorrow.

This is going to be fun.

Victor

---

### Email 4: Day-of reminder (Send on December 22nd afternoon)

**Subject:** See you in a few hours!

**Body:**

Hey {{ subscriber.first_name }},

Tonight's the night! Our workshop starts at 7:00 PM UK.

**Click here to join:** [PLACEHOLDER: INSERT GOOGLE MEET LINK FOR DEC 22]

I'd suggest joining 5 minutes early so you're all set up when we begin.

Get your clay and materials ready, find a comfortable spot, and let's make something beautiful together.

Your ornaments will be ready to hang by Christmas Eve!

See you tonight,
Victor

---
---

## HOW TO SET THIS UP IN CONVERTKIT

I've created these tags for you:
- **Christmas Ornaments Workshop 2024** (main tag - all signups)
- **Workshop Dec 21** (only Dec 21st signups)
- **Workshop Dec 22** (only Dec 22nd signups)

### Step 1: Create two sequences
1. Go to **Send** → **Sequences**
2. Click **+ New Sequence**
3. Create "Christmas Workshop - Dec 21st"
4. Add 4 emails, copy content from above
5. Set timing:
   - Email 1: Immediately
   - Email 2: 1 day after previous
   - Email 3: Send on Dec 20th (or set specific date)
   - Email 4: Send on Dec 21st morning
6. Repeat for "Christmas Workshop - Dec 22nd"

### Step 2: Create the automations (super simple now!)

**Automation 1: December 21st Workshop**
1. Go to **Automate** → **Visual Automations** → **New Automation**
2. Trigger: **Tag added** → select "Workshop Dec 21"
3. Action: **Email sequence** → select "Christmas Workshop - Dec 21st"
4. Save & turn on

**Automation 2: December 22nd Workshop**
1. Create another new automation
2. Trigger: **Tag added** → select "Workshop Dec 22"
3. Action: **Email sequence** → select "Christmas Workshop - Dec 22nd"
4. Save & turn on

### Step 3: Test it
1. Sign up on your landing page with a test email
2. Select December 21st
3. Check ConvertKit - you should see:
   - Tagged with "Christmas Ornaments Workshop 2024"
   - Tagged with "Workshop Dec 21"
   - Custom field `workshop_date` = "Sunday, December 21st - 2:00 PM UK"
   - Added to the Dec 21st sequence
4. Repeat test with December 22nd option
