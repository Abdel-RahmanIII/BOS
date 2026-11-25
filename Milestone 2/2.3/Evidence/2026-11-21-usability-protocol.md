# BarberQueue Egypt usability test protocol

**Pre-test protocol dated 21 November 2026**

This evidence copy was recovered from the saved record of the pre-test protocol. The Egyptian Arabic task prompts were recovered from the prototype. The protocol describes the planned procedure. Section 2.3 records what happened during the test, including the actual sample and device.

## Assumption and success thresholds

Test Milestone 1 assumption #3 with 10 target customers and 3 barbershop receptionists. At least 8 of 10 customers must complete the task correctly and unaided within 60 seconds. All 3 receptionists must complete it correctly and unaided within 15 seconds. Both groups must meet their thresholds.

## Task prompts

Read or show the prompt in the participant's preferred language and give them time to understand it before pressing **Start**.

### Customer

**English**

> You want a haircut with Omar. Check his current wait time, then reserve a haircut with him for one of today's available times.

**Egyptian Arabic**

> عايز تقص شعرك عند عمر. شوف وقت الانتظار عنده دلوقتي، وبعدها احجز عنده قص شعر في أي ميعاد متاح النهارده.

### Receptionist

**English**

> A walk-in wants a haircut with Omar. Add the customer to Omar's queue.

**Egyptian Arabic**

> في عميل جه من غير حجز وعايز يقص شعره عند عمر. ضيف العميل لطابور عمر.

## Session procedure

1. Recruit customers who visit men's barbershops and receptionists who handle walk-ins. Plan one first attempt per participant. The planned devices are a phone for the customer and a front-desk tablet or familiar device for the receptionist. Record the device, language and test mode. Observe remote sessions live over screen share if used.
2. Verify that both in-person role links open their consent screens. Use the study instance for real sessions and keep rehearsal data separate.
3. Explain the purpose of the study, that participants can stop at any point, and that course evidence uses coded IDs. Obtain consent before Start. Use participant codes C01–C10 and R01–R03 in the moderator log. Keep identifying details private.
4. The participant presses **Start** after reading or hearing the prompt. Timing ends at **Confirm reservation**, **Add to queue** or explicit abandonment. Stay silent during the timed task. If asked for help, say “Please do what you'd normally do.” Record any hint, pointing, answer or input from someone else as assistance. Let late participants finish.
5. Wait for **Response saved**. If saving fails, retry in the same tab. Count an abandonment caused by inability to finish as a failure. Document verified technical interruptions and use a fresh eligible participant to replace a voided session.
6. Match each result to the moderator log by session ID and keep names hidden in evidence. After the attempt, ask customers what wait time they saw for Omar and record the answer separately from task scoring. The prototype shows 25 minutes. Ask both roles where they hesitated and open a fresh attempt for the next participant.

## Scoring

| Role | Correct completion | Pass |
| --- | --- | --- |
| Customer | Open Omar's wait view, select Haircut, and submit a reservation with Omar for any available time today. | Correct and unaided within 60 seconds. |
| Receptionist | Submit a Haircut walk-in to Omar's queue. | Correct and unaided within 15 seconds. |

Score by the prototype's recorded completion status, task correctness and elapsed milliseconds, together with the moderator's assistance observation. A wrong barber or service, a missing wait view on the customer task, a late finish, assistance or abandonment fails that attempt. The wait-view event records navigation. Use the follow-up answer to assess comprehension.

Record the participant code, session ID, role, language, test mode, device, outcome, elapsed milliseconds, correctness, assistance status, pass or fail, and any observed issue or interruption.
