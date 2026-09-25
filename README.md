# FlowQ: Virtual Front Desk Queue Management System

An operational workflow solution built for **Henry Ford Health** to mitigate patient throughput bottlenecks in high-volume, walk-in ancillary services. This web application optimizes waiting room congestion, enhances registrar collaboration, provides data-driven performance metrics, and ensures data safety for sensitive PHI/PII.

## 🚀 Tech Stack
* **Frontend Framework:** Next.js
* **Database & Backend:** Supabase
* **Authentication & Integration:** Epic Sandbox Environment (SMART on FHIR)

---

## 💻 Usage & Perspectives

### 👥 Patient Perspective

#### 1. Registration Home Page
* Complete the electronic check-in form to join the virtual queue.
* *[Insert Screenshot of completed form]*

#### 2. Check-In Confirmation
* Receive immediate confirmation and view the department’s real-time average wait time.
* *[Insert Screenshot of check-in confirmation]*

---

### 🩺 Registrar Perspective

#### 1. Employee Login
Click **Employee Login** to authenticate via the Epic FHIR sandbox environment. 

| Name | User Login | User Password |
| :--- | :--- | :--- |
| FHIR, USER | `FHIR` | `EpicFhir11!` |
| FHIRTWO, USER | `FHIRTWO` | `EpicFhir11!` |

**[Insert Screenshot of Epic Login Page with credentials]*

#### 2. Dashboard & Queue Management
* **Live Queue View:** Monitor patient visit data including name, arrival time, reason for visit, active status, and elapsed wait time.
* *[Insert Screenshot of queue dashboard]*

#### 3. Queue Filtering
Toggle view modes to streamline workflow distribution:
* **All Patients:** Displays all records across every stage.
* **Ready for Reg:** Filters for patients waiting to be picked up by a frontline representative.
* **In Progress:** Tracks patients currently undergoing active registration.
* *[Insert Video of flipping through filters]*

#### 4. Operational Actions
* **Assign Registrar:** Select a pending patient and click **Assign** to claim the record under your active logged-in session.
* **Complete Registration:** Click **Complete** upon finishing the check-in process to successfully archive and remove the patient from the live queue.

---

## 📊 Analytics & Reports Page
Gain actionable insight into front-end hospital operations:
* Track total completed registrations and departmental average processing duration.
* Benchmark average registration times isolated by individual frontline staff members.
* Identify high-volume trends by visualizing overall average wait times and daily peak hours.
* *[Insert Screenshots of report page]*
