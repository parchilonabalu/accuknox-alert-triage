# AccuKnox - Alert Triage Workflow (Assessment 2)

### 1. Problem Statement
Security engineers get 100+ alerts daily. No context, need to switch 4-5 tools to investigate one alert. Takes 2 hours to resolve.

### 2. User Persona
Name: Arjun, Security Engineer
Experience: 2 years, manages 50+ cloud accounts
Goal: Resolve critical alerts within 30 mins
Pain Points: No timeline, no logs in one place, can't find root cause fast

### 3. My Solution - 3 Screen Wireframe
**Screen 1: Alert List View**
- Table with Alert ID, Severity (Critical/High/Medium), Resource, Time
- Filters: Severity, Status (Open/Assigned/Resolved), Search bar
- Sort by Critical on top

**Screen 2: Alert Detail View**
- Left: What happened, Affected Resource, Risk Score
- Middle: Timeline of events (when alert triggered, logs)
- Right: Related Logs / Evidence

**Screen 3: Action Panel**
- Auto-suggested Fix from AccuKnox knowledge base
- Buttons: Assign to teammate, Mark as False Positive, Resolve
- Slack Integration button

### 4. Prioritization (Why this order?)
1. Severity Filter first - Engineers must see Critical first to save time
2. Detail with Timeline second - Context is needed for root cause
3. Auto Fix third - Reduces manual effort

### 5. Success Metrics
- MTTR reduced from 2 hours to 30 mins
- Time to mark false positive reduced by 50%
- Single pane investigation (no tool switching)

### 6. Dev Action Items (Engineering Tasks)
1. Backend: Create /api/alerts with severity filter
2. Frontend: Build Timeline component + Log viewer
3. AI Team: Auto-fix suggestion logic
4. Integration: Slack notification for Critical alerts

### 7. Figma Link
https://www.figma.com/design/wRW4070ml7gYylIRlcZKzI/Untitled?node-id=0-1&t=VMR3I9ksMWPxBdmU-1

### 8. Screenshots
[Upload Figma screenshots here]
