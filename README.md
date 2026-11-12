# Celsia

A web app for a virus quarantine and treatment facility. It helps nurses, doctors and admin staff keep track of daily temperatures, doctor visits and discharges, so nobody has to guess who has been measured, who has been seen, and who can go home.

**Live link:** [paste your Vercel link here]
**Built by:** Aryan Purwar
**Built with:** HTML, CSS and vanilla JavaScript. The code was generated with [name of the AI tool you used] and then tested and edited by me.

---

## The problem

The centre has 74 beds, all full. Nurses write temperatures in a journal, and doctors read the journal to decide treatment and discharges. Because of this:

- some patients get measured twice in a day and some not at all
- doctors sometimes visit before the temperature is taken
- patients stay an extra day or two because the discharge message reaches admin late
- there is no way to compare the centre's results with the 85% cure benchmark

## Users and what each can do

| | Nurse | Doctor | Admin |
|---|---|---|---|
| Record temperature | Yes | No | No |
| Log a visit and treatment notes | No | Yes | No |
| Confirm discharge | No | Yes | No |
| Record a death | No | Yes | No |
| Admit a patient | No | No | Yes |
| Process a confirmed discharge | No | No | Yes |
| See the dashboard and activity log | No | No | Yes |

## Screens

1. Role select (login)
2. Nurse: temperature round with Pending, Done and All filters
3. Doctor: rounds (Ready to see, Awaiting temperature, Seen today, Discharge candidates)
4. Admin: dashboard (occupancy,
