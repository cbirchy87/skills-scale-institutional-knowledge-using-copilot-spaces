# Change Request Tracking Template

## Purpose
This template helps the Change Control Coordinator manage and track change requests throughout the project lifecycle, ensuring all changes are properly evaluated, approved, and documented.

## Project Information
- **Project Name**: _[Enter project name]_
- **Change Control Coordinator**: _[Name]_
- **Project Manager**: _[Name]_
- **Product Manager**: _[Name]_
- **Document Version**: _[Version number]_
- **Last Updated**: _[Date]_

---

## Change Control Process Overview

### Change Request Lifecycle
1. **Submit**: Requester submits change request with justification
2. **Review**: Change Control Coordinator reviews for completeness
3. **Assess**: Impact analysis performed (scope, schedule, resources, risks)
4. **Approve/Reject**: Decision made by appropriate authority
5. **Implement**: Approved changes integrated into project plan
6. **Verify**: QA Specialist validates change implementation
7. **Close**: Change documented and closed

### Change Authority Matrix
| Change Type | Approval Authority | Typical Timeline |
|-------------|-------------------|------------------|
| Minor (low impact) | Project Manager | 1-2 days |
| Moderate (medium impact) | Product Manager + PM | 3-5 days |
| Major (high impact) | Stakeholders + Sponsors | 1-2 weeks |
| Emergency | Emergency Change Board | 24 hours |

---

## Change Request Form

### CR-[XXX]: [Change Title]

**Submission Date**: _[Date]_  
**Submitted By**: _[Name, Role]_  
**Priority**: ☐ Low  ☐ Medium  ☐ High  ☐ Critical  
**Status**: ☐ Submitted  ☐ Under Review  ☐ Approved  ☐ Rejected  ☐ Implemented  ☐ Closed

---

### 1. Change Description
**Current State**: _[Describe what exists today]_

**Proposed Change**: _[Describe what should change]_

**Justification**: _[Why is this change needed?]_
- Business value:
- Customer impact:
- Risk mitigation:
- Other reasons:

---

### 2. Impact Analysis

#### Scope Impact
- [ ] **No impact**: Change contained within existing scope
- [ ] **Minor expansion**: Small addition to current scope
- [ ] **Moderate expansion**: Notable scope addition
- [ ] **Major expansion**: Significant scope change
- [ ] **Scope reduction**: Removing planned functionality

**Details**: _[Explain scope impact]_

#### Schedule Impact
- [ ] **No impact**: No effect on timeline
- [ ] **Minor delay**: 1-3 days delay
- [ ] **Moderate delay**: 4-10 days delay
- [ ] **Major delay**: >10 days delay or milestone shift
- [ ] **Accelerates**: Reduces timeline

**Estimated Delay/Acceleration**: _[X days/weeks]_  
**Affected Milestones**: _[List affected milestones]_

#### Budget/Resource Impact
- [ ] **No impact**: No additional resources needed
- [ ] **Minor impact**: Slight increase in existing resources
- [ ] **Moderate impact**: Additional resources required
- [ ] **Major impact**: Significant resource changes needed

**Estimated Cost**: _[$X or X hours/days]_  
**Resource Requirements**: _[What resources are needed]_

#### Quality Impact
- [ ] **Improves quality**: Enhances product quality
- [ ] **No impact**: No effect on quality
- [ ] **Requires additional testing**: QA effort needed
- [ ] **May introduce risks**: Quality concerns exist

**QA Assessment**: _[Input from QA Specialist]_

#### Risk Impact
- [ ] **Reduces risk**: Mitigates existing risks
- [ ] **No impact**: No effect on risks
- [ ] **Introduces new risks**: Creates new risk exposure

**Risk Assessment**: _[Input from Risk Manager]_  
**New/Modified Risks**: _[List risks]_

---

### 3. Affected Stakeholders
List all parties impacted by this change:
- [ ] Development team
- [ ] QA/Testing team
- [ ] Product management
- [ ] Sales/Marketing
- [ ] Customer support
- [ ] End users
- [ ] External vendors/partners
- [ ] _[Others]_

**Stakeholder Notification Plan**: _[How and when will stakeholders be informed]_

---

### 4. Dependencies
**Internal Dependencies**:
- _[List dependent features, teams, or activities]_

**External Dependencies**:
- _[List external vendors, systems, or factors]_

**Dependency Coordination**: _[How dependencies will be managed]_

---

### 5. Implementation Plan

**Implementation Approach**: _[Brief description of how change will be implemented]_

**Implementation Steps**:
1. _[Step 1]_
2. _[Step 2]_
3. _[Step 3]_

**Estimated Effort**: _[Hours/days]_

**Assigned To**: _[Name]_

**Target Implementation Date**: _[Date]_

**Testing Requirements**:
- [ ] Unit tests
- [ ] Integration tests
- [ ] Regression tests
- [ ] User acceptance tests
- [ ] Performance tests
- [ ] Security tests

---

### 6. Rollback Plan

**Rollback Strategy**: _[How can this change be reversed if needed]_

**Rollback Triggers**: _[What conditions would require rollback]_

**Rollback Effort**: _[Estimated time/effort to rollback]_

---

### 7. Change Review and Assessment

**Reviewed By**: _[Change Control Coordinator name]_  
**Review Date**: _[Date]_

**Completeness Check**:
- [ ] All required fields completed
- [ ] Justification is clear and compelling
- [ ] Impact analysis is thorough
- [ ] Stakeholders identified
- [ ] Implementation plan is feasible

**Assessment Summary**: _[Coordinator's overall assessment]_

**Recommendation**: ☐ Approve  ☐ Reject  ☐ Defer  ☐ Request More Information

**Rationale**: _[Reason for recommendation]_

---

### 8. Approval Decision

**Decision Date**: _[Date]_  
**Decision**: ☐ Approved  ☐ Approved with Conditions  ☐ Rejected  ☐ Deferred

**Approved By**:
| Role | Name | Signature | Date |
|------|------|-----------|------|
| Project Manager | _[Name]_ | | |
| Product Manager | _[Name]_ | | |
| Risk Manager | _[Name]_ | | |
| _[Other Approver]_ | _[Name]_ | | |

**Conditions** (if applicable): _[Any conditions or constraints on the approval]_

**Rejection Reason** (if applicable): _[Why the change was rejected]_

**Deferral Reason** (if applicable): _[Why the change was deferred and when to revisit]_

---

### 9. Implementation Tracking

**Implementation Started**: _[Date]_  
**Implementation Completed**: _[Date]_

**Implementation Notes**: _[Any deviations from plan, issues encountered, resolutions]_

**Testing Completed**: _[Date]_  
**QA Sign-Off**: _[QA Specialist name, date]_

**Documentation Updated**:
- [ ] Requirements updated
- [ ] Design documents updated
- [ ] Test cases updated
- [ ] User documentation updated
- [ ] Release notes updated
- [ ] Training materials updated

---

### 10. Verification and Closure

**Verification Date**: _[Date]_

**Verification Checklist**:
- [ ] Change implemented as approved
- [ ] All testing completed successfully
- [ ] No unintended side effects observed
- [ ] Documentation updated
- [ ] Stakeholders notified
- [ ] Project plan updated

**Actual Impact** (compare to estimated):
- **Scope**: _[Actual scope impact]_
- **Schedule**: _[Actual schedule impact]_
- **Resources**: _[Actual resource impact]_
- **Quality**: _[Actual quality impact]_

**Lessons Learned**: _[What went well, what could be improved]_

**Closed By**: _[Change Control Coordinator name]_  
**Closure Date**: _[Date]_

---

## Change Request Log

Track all changes in a central log:

| CR ID | Title | Submitted | Priority | Status | Approval Date | Impact | Notes |
|-------|-------|-----------|----------|--------|---------------|--------|-------|
| CR-001 | _[Title]_ | _[Date]_ | High | Approved | _[Date]_ | Schedule +3d | _[Note]_ |
| CR-002 | _[Title]_ | _[Date]_ | Low | Rejected | _[Date]_ | N/A | _[Note]_ |
| CR-003 | _[Title]_ | _[Date]_ | Medium | Implemented | _[Date]_ | Scope +5% | _[Note]_ |

---

## Change Metrics and Reporting

### Monthly Change Statistics
- **Total Changes Submitted**: _[Number]_
- **Changes Approved**: _[Number]_ (_[Percentage]_)
- **Changes Rejected**: _[Number]_ (_[Percentage]_)
- **Changes Deferred**: _[Number]_ (_[Percentage]_)
- **Average Approval Time**: _[Days]_
- **Average Implementation Time**: _[Days]_

### Change Impact Summary
- **Cumulative Schedule Impact**: _[Total days added/removed]_
- **Cumulative Budget Impact**: _[Total cost]_
- **Scope Variance**: _[Percentage change]_

### Change Trend Analysis
- **Most Common Change Type**: _[Type]_
- **Most Impactful Changes**: _[List]_
- **Change Request Sources**: _[Breakdown by requester type]_

---

## Emergency Change Process

For critical issues requiring immediate changes:

### Emergency Change Criteria
- [ ] Production outage or critical defect
- [ ] Security vulnerability requiring immediate fix
- [ ] Regulatory/compliance issue
- [ ] Data integrity risk

### Emergency Change Procedure
1. **Immediate notification** to Change Control Coordinator, PM, and stakeholders
2. **Rapid assessment** (within 2 hours)
3. **Emergency Change Board decision** (within 4 hours if possible)
4. **Expedited implementation** with heightened monitoring
5. **Retrospective review** within 24 hours post-implementation

### Emergency Change Board
- Change Control Coordinator
- Project Manager
- Product Manager
- Risk Manager
- Technical Lead
- _[Other key stakeholders]_

---

## Change Control Best Practices

### For Requesters
- Submit changes as early as possible
- Provide complete information to avoid delays
- Clearly articulate business value
- Consider alternatives and trade-offs

### For Change Control Coordinator
- Review changes promptly (within 1 business day)
- Facilitate efficient approval process
- Maintain accurate and up-to-date change log
- Communicate decisions and rationale clearly
- Track change metrics for process improvement

### For Approvers
- Evaluate changes against project goals and constraints
- Consider cumulative impact of all changes
- Balance agility with stability
- Document decision rationale

---

## Notes
_[Project-specific notes, special considerations, or deviations from standard process]_
