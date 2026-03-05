### 🚢 Dry Dock Execution & Closing (Test Suite)

| TC ID | Test Scenario | Test Case | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- |
| **MAMS_DD_DR_03** | Daily Progress | Select Vessel from dropdown | System loads only **Approved** vessels | ✅ Passed |
| **MAMS_DD_DR_20** | Daily Progress | Future dates in Date of Report | System validates/blocks future dates | ✅ Passed |
| **MAMS_DD_CD_12** | Dock Closing | Set End Date earlier than Start Date | Validation Error: "End Date cannot be earlier than Start Date" | ✅ Passed |
| **MAMS_DD_CD_13** | Dock Closing | Select Vessel with no approved projects | Project dropdown should be empty | ✅ Passed |
| **MAMS_DD_CD_16** | Security | Log in with "View-Only" role | Action buttons (Save/Delete) are disabled | ✅ Passed |
