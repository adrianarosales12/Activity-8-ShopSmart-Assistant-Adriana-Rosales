# Activity 8: ShopSmart Assistant — An Expert System for Customer Decisions
## Sessions 15
## Due date (mm/dd/yyyy): 09/27/2026
## Adriana Rosales González
## Delivery Format: [] Video URL | [X] Markdown file | [] Jupyter Notebook file

---

# Activity Description

## The Story

**ShopSmart** is a fictional online store. Every day, it has to make small decisions
automatically: should this customer get a discount? Should this order get free shipping?
Should this account be locked for suspicious activity? Should IT be alerted about an
overheating server?

Instead of a human deciding each case one by one, ShopSmart uses an **expert system**: a fixed
set of IF-THEN rules, written once by a human expert, applied automatically and consistently by
a computer. This activity explores how that works — the same idea shows up in IT (security
rules), business (discount and shipping rules), and any interface that has to *explain itself*
to the people using it (a design/UX concern too).

This activity is a single interactive app — no coding required. Everyone in the class uses the
**same fixed rule base and the same five customer/system profiles** (there is no randomness
anywhere in the app), so your results should match your classmates' exactly.

**App link:** https://uam-aiclass-a8.streamlit.app/

If you'd rather run it on your own machine instead of using the shared link, see
**Running It Yourself** below.

### The App

The app has two tabs:

1. **🧠 Knowledge Base & Architecture** — how the five standard components of an expert system (knowledge base, inference engine, user interface, knowledge acquisition, explanation mechanism) map onto this specific app, plus the full rule base and the five fixed profiles.
2. **⚙️ Run the Inference Engine** — pick one of the five profiles, then click through the engine checking each rule against it, one at a time, showing exactly which condition passed or failed and why.

---

### Your Tasks

1. **Read the Knowledge Base & Architecture tab.** Note the five components and the four rules.
  

2. **Run each of the five profiles (A through E) through the Inference Engine tab**, one at a
   time, clicking through all four rules for each. Take a screenshot of the **Final Summary**
   for each profile.


### Profile A — Camila R. (Loyal Shopper)
- **Final Summary:** 1 of 4 rules fired.
- **Conclusion:** Offer a 10% discount on the next purchase.
- **Comment:** Camila is a returning customer with 650 loyalty points, so the loyalty discount rule fired. Other rules did not apply.
 <img width="553" height="592" alt="image" src="https://github.com/user-attachments/assets/e922f209-93f5-4e22-81eb-9839e10c0933" />
<img width="308" height="110" alt="image" src="https://github.com/user-attachments/assets/b349d32b-ee16-40f7-9447-b2f508826793" />

### Profile B — New Visitor
- **Final Summary:** 1 of 4 rules fired.
- **Conclusion:** Unlock free shipping.
- **Comment:** Although this visitor has no loyalty points, the cart total is $150 and they are on the checkout page, so the free shipping rule fired.
<img width="428" height="607" alt="image" src="https://github.com/user-attachments/assets/f8fdb505-4530-4ec1-8bc5-dd09c3157d50" />
<img width="200" height="89" alt="image" src="https://github.com/user-attachments/assets/5e852a3b-d14f-4f77-b258-fb8a672c26ee" />

### Profile C — Suspicious Login (Flagged IP)
- **Final Summary:** 1 of 4 rules fired.
- **Conclusion:** No rules applied.
- **Comment:** Even though this profile has loyalty points, they are not on the checkout page. The flagged IP prevents the account lockout rule from firing. No benefits or alerts were triggered.

<img width="433" height="596" alt="image" src="https://github.com/user-attachments/assets/1a43a378-4fbb-4f59-b26e-141d5d6bb9da" />
<img width="255" height="87" alt="image" src="https://github.com/user-attachments/assets/06d7ceda-7990-4038-a1c1-b212de8b3623" />

### Profile D — Big Spender, System Under Load
- **Final Summary:** 4 of 4 rules fired.
- **Conclusion:** Offer a 10% discount, unlock free shipping, and trigger emergency cooling/alert IT.
- **Comment:** This profile qualifies for loyalty discount (1200 points), free shipping (cart total $250), and server alert (system under load). Only the account lockout rule did not apply.

<img width="554" height="625" alt="image" src="https://github.com/user-attachments/assets/4d6cfc54-ff7c-42ef-b44d-4e99c91f2aa4" />
<img width="259" height="182" alt="image" src="https://github.com/user-attachments/assets/ac5be8bc-804a-423d-9f8a-264c9f1b0a1f" />

### Profile E — Quiet Night
- **Final Summary:** 0 of 4 rules fired.
- **Conclusion:** No rules applied.
- **Comment:** This profile is not a returning customer, has no loyalty points, no checkout activity, and no system stress. Therefore, none of the rules fired.
<img width="449" height="584" alt="image" src="https://github.com/user-attachments/assets/d0ef7fc1-6a6a-49d3-b6b8-ad12acf47c24" />
<img width="233" height="77" alt="image" src="https://github.com/user-attachments/assets/e4eceb4c-66d7-4000-90da-a92718b0cc38" />


---
3. **A8_ReflectionQuestions.md`**

**1. Match each of the five expert-system components to what it is **in this specific app**:
   Knowledge base, Inference engine, User interface, Knowledge acquisition mechanisms,
   Explanation mechanisms.**

 - Knowledge base: This is the set of four IF–THEN rules (R1–R4) plus the fixed customer/system profiles (A–E). It represents all the knowledge encoded by human experts that the system can use to make decisions.
- Inference engine: The part of the app that applies the rules to the facts in each profile. It checks conditions one by one, decides whether they are satisfied, and determines which rules “fire.”
- User interface: The Streamlit app itself — the two tabs where you can read the rules, select a profile, click through the inference process, and view the Final Summary. It’s how humans interact with the system.
- Knowledge acquisition mechanisms: In this app, it’s the original process of encoding the rules and profiles into the system. A human expert wrote them once, and they are fixed — no randomness or learning.
- Explanation mechanisms: The step-by-step display that shows why each rule fired or failed, plus the Final Summary. This makes the system transparent and easy to understand.


**2. Fill in the blank: the IF-THEN format used by every rule in ShopSmart's knowledge base is
   traditionally called a **______ rule**.**
- The IF–THEN format used by every rule in ShopSmart’s knowledge base is traditionally called a production rule.
- Production rules are the standard way expert systems represent knowledge: each rule has conditions (IF) and actions (THEN).


**3. For **Profile A**, which rule(s) fire, and what is the resulting conclusion?**
- Rule(s) fired: R1 — Loyalty Discount.
- Resulting conclusion: Offer a 10% discount on the next purchase.
- Explanation: Camila is a returning customer with 650 loyalty points, which satisfies both conditions of R1. However, her cart total is only $45, so she does not qualify for free shipping (R2). No IT rules apply because there are no failed logins or server stress.


**4. For **Profile B**, which rule(s) fire, and what is the resulting conclusion?**
- Rule(s) fired: R2 — Free Shipping.
- Resulting conclusion: Unlock free shipping.
- Explanation: Even though this visitor is not a returning customer and has zero loyalty points, they are on the checkout page with a cart total of $150. That satisfies both conditions of R2, so free shipping is granted. No other rules apply.

**5. For **Profile C**, does the **Account Lockout (R3)** rule fire? Name the exact condition
   (fact name and its actual value for Profile C) that determines the answer.**
- Does R3 fire? No.
- Condition determining the answer: ip_flagged = True.
- Explanation: The Account Lockout rule requires failed_logins > 3 and ip_flagged = False. Profile C has a flagged IP, so the condition fails. Even though this profile has 800 loyalty points, they are not on the checkout page, so no business rules fire either. The Final Summary shows no rules applied.

**6. For **Profile D**, how many rules fire in total? List every resulting conclusion.**
- Total rules fired: 3 (R1, R2, R4).
- Resulting conclusions:
  - Offer a 10% discount (loyalty points = 1200).
  - Unlock free shipping (cart total = $250, checkout page = True).
  - Trigger emergency cooling and alert IT (CPU load and temperature above thresholds).
- Explanation: This profile represents a heavy shopper during a stressed system. It qualifies for both business benefits and an IT alert. Only the Account Lockout rule does not apply because there are no failed logins.

**7. For **Profile E**, how many rules fire? What does the Final Summary say?**
- Total rules fired: 0.
- Final Summary: No rules applied.
- Explanation: This profile has no loyalty points, is not a returning customer, is not on the checkout page, and shows no IT issues. Therefore, none of the rules are triggered.

**8. True or False: ShopSmart's inference engine starts from a hypothesis (like "this account
   should be locked") and works backward to check whether the facts support it. Justify your
   answer using the term **"forward chaining"** or **"backward chaining."****

   
False.  
- ShopSmart’s inference engine uses forward chaining. That means it starts from the known facts in each profile (e.g., loyalty points, cart total, server load) and moves forward, checking each rule to see if the conditions are satisfied. Backward chaining would start from a hypothesis (like “this account should be locked”) and work backward to see if the facts support it, but that is not how this app works.

**9. Propose **one new IF-THEN rule**, written in the same format as R1–R4, that ShopSmart could
   add for IT, Business, or a user-experience/design concern not already covered by the
   existing four rules. State which department it belongs to.**
- R5 — Cart Abandonment Reminder (UX/Business)
- IF on_checkout_page = True AND cart_total > 0 AND checkout_inactivity_minutes > 10 THEN send a reminder notification to the customer.

  - Department: User Experience / Business.
- Explanation: This rule would help reduce cart abandonment by reminding customers who leave items in their cart without completing checkout. It adds a UX-focused decision not covered by the existing rules.


---
# References:
- [Streamlit documentation](https://docs.streamlit.io/)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
