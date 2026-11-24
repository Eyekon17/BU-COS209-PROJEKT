# PRODUCT NAME: K RIDE

## PRODUCT OVERVIEW
A student-based application whose purpose is to help locate and assign campus transportation systems which aids the riders to access students seamlessly and vice versa within the academic community.

## REASON FOR BUILDING IT / PROBLEM
After surveying and careful analysis, the report shows how students face unpredictable wait times, peak hour congestion between classes and hostels. Even sometimes unclear fare expectations, difficulty locating tricycles around campus.

And on the part of the rider, they experience idle time and uneven passenger distribution across the school campus whereby in the walls of BABCOCK university, a student is going to BUTH and another is going to the school stadium, both are going to different routes the rider would not be able to carry the two of them hence having to carry one and leave the other .

## PRODUCT VISION
A two sided campus mobility system (student app + rider app) that enables students to request or access nearby tricycles and tricycle riders to discover, accept and pick up students safely, transparently and in alignment with Babcock university transport rules.

## TARGET USERS AND PERSONAS
**Babcock students (Riders / passengers):**
* Undergraduate and post graduate students moving between hostels, lecture halls, libraries, cafeterias, and Babcock University Teaching Hospital (BUTH). Require fast pickup, clear fares, and campus-safe verification.

## How Two-Way Access Works
* **Student-to-Rider:** Students broadcast pickup requests with exact pins (e.g., specific hostel, faculty, block, or cafeteria) and destination zones. Nearby available riders see the request and accept it.
* **Rider-to-Student:** Riders toggle online, view a live demand heatmap/queue of waiting students by zone, and either accept direct requests or broadcast their live location/ETA along a corridor (e.g., heading from hostels to academic area) so waiting students can claim a seat.

## Core Features & Functional Requirements

### Student Experience
* **Campus Authentication:** Sign up with a verified Babcock student email/matriculation ID.
* **Pin-Drop & Landmark Picker:** Select exact pickup and drop-off points using curated campus landmarks (halls of residence, faculties, library, main gates/junctions) plus GPS pin adjustment.

### Ride Modes
* **Instant Request:** Request a tricycle to your pin.
* **Shared / Corridor Match:** Join a tricycle heading along a popular route to split/keep fares low.
* **Fare Transparency:** Display standard approved campus fare ranges upfront before booking to prevent overcharging.
* **Live Trip Tracking & Safety:** View rider name, photo, verified tricycle number (e.g., KEKE-01), live GPS progress, and an SOS/report button tied to campus transport/security.
* **Rating & Issue Reporting:** Rate trips and log complaints (overcharging, speeding, rude conduct, or route refusal) directly against the tricycle ID.

### Tricycle Rider Experience
* **Online / Offline Toggle & Shift Status:** Simple, high-contrast UI built for quick glances while parked or between trips.
* **Demand View (Access to Students):** Live map/list showing student pickup pins and headcounts per campus zone so riders can position themselves where demand is high.
* **Request Management:** Accept or decline incoming student requests with clear pickup pin, destination, and estimated fare.
* **Active Trip & Earnings Summary:** Navigate to pickup and drop-off, mark trip complete, and view daily trip count and estimated earnings.

### Admin & Operations Dashboard
* **Rider & Fleet Registry:** Approve/suspend rider accounts and link each profile to an official tricycle number.
* **Fare & Zone Configuration:** Set base fares, peak/off-peak rules, and allowed pickup/drop-off zones.
* **Incident & Complaint Queue:** Review student reports (over speeding, fare disputes, no-shows) with trip logs and tricycle numbers.

## Non-Functional Requirements
* **Low-Data & Low-Bandwidth Friendly:** Lightweight screens and compressed map tiles for patchy campus/rural-edge network conditions.
* **Usability & Accessibility:** Large tap targets, clear typography, and minimal steps (request a ride in 3 taps or fewer).
* **Security & Privacy:** Mask personal phone numbers via in-app messaging/calling where possible; restrict platform access to verified campus users and approved operators.
* **Reliability:** Target 99.5%+ uptime during academic semesters and peak class changeovers.

## User Flows
1. **Student Requests a Ride:** Open app → Select pickup landmark & destination → See approved fare & nearby tricycle → Tap Request → Rider accepts → Track arrival → Board & complete trip → Rate/report if needed.
2. **Rider Finds & Picks Up Student:** Toggle Online → View nearby student requests or high-demand zone → Tap Accept → Drive to student pin → Confirm pickup & drop-off → Complete trip.

## Payment Plan
* **Payment from the student:**
  When signing up for the app for the first time one of the requirements will be the account details of the rider to ensure seamless transactions and avoid time wastage for both the student and the rider. While placing the ride the student will see a module pop up after selecting the driver and will see the details which the rider had imputed earlier.
* **Payment confirmation:**
  After the student has paid the rider will confirm if he has seen the money or not providing a seamless transaction between the rider and student.
* **Fraudulent activities:**
  In the case of fraudulent activities there would be a help center for both rider and student to complain about specific issues especially fake transfers from either parties.

## Success Metrics (KPIs)
* **Liquidity & Speed:** Average match time (target < 2 minutes) and average pickup arrival time during peak hours.
* **Adoption:** Weekly active students and percentage of registered campus tricycles active daily.
* **Reliability:** Ride completion rate (%) and cancellation rate (%).
* **Safety & Compliance:** Number of fare/over speeding complaints per 1,000 trips and average time to resolve reported issues.
### MVP

Project concept

### 1. Project overview

The proposed application is a campus-based ride-hailing platform that connects students who need transportation with Keke drivers operating within the university.

The app will allow students to request rides, share their pickup locations and communicate their destinations to available drivers. Drivers will be able to receive ride requests, view pickup locations and accept requests.

## 2. Problem statement

Students often experience difficulties finding available transportation within the university campus, particularly when they need to travel between lecture halls, hostels, administrative buildings and other campus locations.

Similarly, Keke drivers may find it difficult to identify students who require transportation.

The proposed application aims to simplify this process by creating a centralized platform that connects students with available drivers.

## 3. Proposed solution

Developing a mobile ride-hailing app managed by the university that allows students to:-

* Register and log in.

* Share their current location.

* Enter their desired destination.

* Request a Keke ride.

* View the driver's details.

* Track the status of their ride request.

Drivers will have a seperate interface through which they can receive and accept ride requests.

## 4. Core MVP features


Feature                    Student       Driver
Registration                yes          yes 
Location sharing            yes          View student’s location        
Destination selection       yes          yes
Request a ride              yes          no
Accept ride requests        no           yes
Ride status                Track status  Update status
Cancel request             yes            yes

 ## 5. Expected outcome

The first version should successfully connect students requesting transportation with available Keke drivers, allowing them to exchange pickup and destination information and complete a basic ride-request process.

## 6. How the application would work

### Student journey

* Open application

    Student logs into their account.

* Share location

    Application obtains the student's current location with permission.

* Enter destination

    Student selects where they want to go.

* Request Keke

    Request is sent to available drivers.

* Driver accepts

    Student receives the driver's information and ride confirmation.

* Ride completed

    Driver marks the ride as completed.