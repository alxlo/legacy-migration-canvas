# Legacy Migration Checklist v3.0 - Workshop Edition

**System Name:** 

**Team:** 

**Date:** 

---

## How to Use This Checklist

This checklist is designed to work with the Legacy Migration Canvas during a 4-6 hour workshop. Questions are prioritized to help you focus on what matters most:

- **P1 (Critical)**: Must address in workshop - drives canvas completion
- **P2 (Important)**: Should address if time permits, or assign as follow-up tasks  
- **P3 (Nice-to-have)**: Additional considerations for comprehensive planning

> **Facilitator Note:** Start with P1 questions to ensure canvas completion. Use P2/P3 to deepen analysis where time allows or create actionable follow-up tasks.

---

## Business Case & Value Proposition
*Why are we doing this & what do we gain?*

### P1 - Critical Workshop Questions

☐ **P1** Have we clearly articulated the business goals for this migration beyond technical improvements?

☐ **P1** Have we identified specific customer/user pain points this migration will address? What are they?

☐ **P1** Have we quantified potential time/cost savings for the business and customers?

☐ **P1** Do we understand how this migration supports the company's long-term strategy?

☐ **P1** Have we identified new business capabilities that will be enabled by the migration?

### P2 - Important Follow-up Questions

☐ **P2** Do we have metrics in place to measure business value before and after the migration?

☐ **P2** Have we secured executive sponsorship with alignment on business objectives?

☐ **P2** Have we aligned with different stakeholders on their specific migration objectives (revenue generation, operational efficiency, risk reduction)?

☐ **P2** Have we identified product lines or features that are unprofitable and could be discontinued rather than migrated?

> **Facilitator Note:** Focus on tangible business value, not just "technical debt reduction." Help the team think like product owners, not just engineers.

---

## Current System Analysis
*What we're working with*

### P1 - Critical Workshop Questions

☐ **P1** Have we thoroughly analyzed the current system architecture and dependencies?

☐ **P1** Do we understand the data models and their business relevance?

☐ **P1** Do we know which legacy features are still used vs. obsolete?

☐ **P1** Have we identified cross-cutting concerns (logging, security, etc.) that need redesign?

### P2 - Important Follow-up Questions

☐ **P2** Do we understand integration points with other systems and their migration impacts?

☐ **P2** Have we identified technical debt that should be addressed during migration?

☐ **P2** Have we evaluated security risks in both the legacy and target systems?

☐ **P2** Have we traced data flows to original sources rather than assuming the legacy system is the source of truth?

*Often better data exists at original source systems that was lost or degraded when passed to legacy systems.*

☐ **P3** Have we identified any critical aggregators (reporting functions crucial to running the business)?

*Reports or data aggregation processes that executives rely on to run the business, which often become bottlenecks in migrations.*

### P3 - Additional Considerations

☐ **P3** Have we analyzed how current business processes are shaped by legacy system constraints?

☐ **P3** Have we explored potential event interception points (messaging, APIs, databases) to enable incremental migration?

*Identify locations where you can intercept data flows between systems to gradually redirect processing to new components.*

> **Facilitator Note:** Don't get lost too deep into technical details in the workshop. Focus on understanding the big picture and identifying what needs deeper analysis.

---

## Stakeholder Needs
*Who's affected & what they actually need*

### P1 - Critical Workshop Questions

☐ **P1** Have we identified all relevant stakeholder groups (end users, business departments, IT, etc.)?

☐ **P1** Have we gathered input from end customers on their needs and pain points?

☐ **P1** Have we engaged with sales/customer service teams to understand customer expectations?

☐ **P1** Do we have a communication plan to keep stakeholders informed throughout the migration?

☐ **P1** Have we established feedback channels for continuous stakeholder input?


### P2 - Important Follow-up Questions

☐ **P2** Have we conducted interviews or observation sessions with frontline employees?

☐ **P2** Have we analyzed support tickets and common user complaints?

☐ **P2** Have we engaged with finance teams to understand revenue impacts of different products/features?

☐ **P2** Have we defined communication cadence and key milestone updates for different stakeholder groups throughout the migration?

*Different stakeholders need different update frequencies - executives might need monthly updates while end users need more frequent communication during their migration phases.*

☐ **P2** Have we established escalation protocols for communicating migration issues or delays to stakeholders?

*Define when and how to communicate problems, who needs to be informed first, and what level of detail different groups require.*


### P3 - Additional Considerations

☐ **P3** Have we identified off-system workarounds (spreadsheets, access databases, etc.) that have evolved around legacy limitations?

☐ **P3** Have we involved stakeholders in identifying meaningful ways to slice the migration?

*Work with business experts to break down the system into logical segments that can be migrated independently, focusing on business value rather than technical boundaries.*

☐ **P2** Do we have a plan for celebrating migration milestones and communicating wins to maintain stakeholder engagement?

*Migration projects can be long - plan for recognizing progress and maintaining momentum through regular success communication.*

> **Facilitator Note:** Technical teams often underestimate stakeholder complexity. Help them understand that "users" includes many different groups with different needs.

---

## Organizational Constraints
*Reality check*

### P1 - Critical Workshop Questions

☐ **P1** Do we have the right mix of technical skills for both legacy and target technologies?

☐ **P1** Have we allocated product management resources to guide the migration?

☐ **P1** Have we budgeted for potential unforeseen technical challenges?

☐ **P1** Do we have access to subject matter experts for critical legacy components?

### P2 - Important Follow-up Questions

☐ **P2** Do we have contingency plans for timeline extensions if needed?

☐ **P2** Have we accurately estimated the total cost of ownership for the new system?

☐ **P2** Have we considered external expertise needs for specialized migration tasks?

☐ **P2** Have we budgeted for the potential parallel running of critical systems during transition phases?

### P3 - Additional Considerations

☐ **P3** Have we allocated resources for implementing and eventually removing transitional architecture components?

☐ **P3** Have we accounted for the time needed to collaborate with business on identifying migration slices?

*Ensure the schedule includes dedicated time for workshops to analyze and define meaningful migration increments.*

> **Facilitator Note:** Be realistic about constraints. Technical teams tend to be optimistic about timelines and underestimate the complexity of organizational coordination.

---

## Quality Goals
*What matters most*

### P1 - Critical Workshop Questions

☐ **P1** Have we identified the top 3-5 most important quality goals for this migration?

☐ **P1** Have we aligned quality goals with key stakeholder concerns and business drivers?

☐ **P1** Have we established measurable criteria for each quality goal?

☐ **P1** Have we prioritized quality goals when they conflict with each other?

### P2 - Important Follow-up Questions

☐ **P2** Have we defined how to measure the success of the migration?

☐ **P2** Do we have plans to collect user feedback after implementation?

☐ **P2** Have we established a process for addressing issues and enhancements post-launch?

☐ **P2** Can we validate that the promised benefits (e.g. faster time to market, lower cost of change) are actually realized?

### P3 - Additional Considerations

☐ **P3** Have we established processes to ensure we don't accumulate technical debt in the new system?

☐ **P3** Do we have a plan for implementing continuous delivery practices that might have been promised in the business case?

> **Facilitator Note:** Quality goals should be specific and measurable, not generic "better performance." Help the team connect quality attributes to real business outcomes.

---

## Technical Constraints
*Technical stuff we can't change*

### P1 - Critical Workshop Questions

☐ **P1** Have we identified legacy interfaces that must be maintained during and after migration?

☐ **P1** Do we understand technology stack requirements or limitations?

☐ **P1** Have we mapped integration points with external systems?

☐ **P1** Do we know infrastructure and deployment constraints we must work within?

### P2 - Important Follow-up Questions

☐ **P2** Have we evaluated what regulatory or compliance requirements constrain our technical choices?

☐ **P2** Do we understand data residency or sovereignty requirements?

*Where data must be stored, how it can be processed, and which laws apply to it based on geographic location.*

☐ **P2** Have we identified any vendor lock-in situations that limit our options?

☐ **P2** Do we know what existing licenses or contracts affect our technology choices?

### P3 - Additional Considerations

☐ **P3** Have we evaluated the impact of existing monitoring and operational tooling on our choices?

☐ **P3** Do we understand network and security constraints that may affect the new architecture?

> **Facilitator Note:** Technical constraints are often the most comfortable area for technical teams, but don't let them get stuck here. Keep the focus on constraints that truly limit options.

---

## Migration Strategy
*How we're going to do this*

### P1 - Critical Workshop Questions

☐ **P1** Have we designed a phased approach that reduces risk?

☐ **P1** Have we identified high-value components to prioritize for early migration?

☐ **P1** Do we have a data migration strategy that ensures business continuity?

☐ **P1** Have we explicitly ruled out big bang approaches in favor of incremental migration?

☐ **P1** Have we explored different slicing approaches?

*Consider options like migrating by product line, user group, business capability, or user journey to find the most effective approach.*

☐ **P1** Have we planned for parallel operations during transition if needed?

☐ **P1** Have we considered tackling critical aggregators (essential reports/functions) early rather than last? Which?

*Consider replacing critical reports first rather than leaving them until the end where they can block complete migration.*

☐ **P1** Have we avoided the feature parity trap by focusing on business needs rather than replicating all existing functionality?

☐ **P1** Have we considered implementing frequent delivery practices from the beginning of the migration to validate future delivery capabilities?

*Resist the temptation to simply recreate the existing system with newer technology.*

### P2 - Important Follow-up Questions

☐ **P2** Have we defined rollback procedures in case of migration issues?

☐ **P2** Do we have a plan for handling legacy system maintenance during migration?

☐ **P2** Have we established a testing strategy for verifying functionality post-migration?

☐ **P2** Have we planned for performance and load testing at each migration phase to ensure the new system can handle production workloads?

*Consider testing both individual migrated components and the overall system performance as load shifts between old and new systems.*

☐ **P2** Do we have a strategy for testing data integrity and consistency between old and new systems during parallel operations?

*Include plans for automated data reconciliation checks and handling of data discrepancies during transition.*

### P3 - Additional Considerations

☐ **P3** Have we explored applying the Strangler Fig and Bridge to the New Town patterns to gradually replace functionality?

*Patterns where new functionality gradually takes over from legacy code by intercepting calls (Strangler Fig) or through intermediate connecting layers during transition (Bridge to the New Town).*

☐ **P3** Have we designed necessary transitional architecture components with clear plans for their eventual removal?

*Temporary components needed during migration that should be removed once they're no longer needed.*

> **Facilitator Note:** Migration strategy often generates the most debate. Focus on establishing principles (incremental, value-driven) rather than detailed execution plans in the workshop.

---

## Key Architectural Decisions
*Critical decisions that shape the migration*

### P1 - Critical Workshop Questions

☐ **P1** Have we made key technology stack decisions for the target architecture?

☐ **P1** Have we decided on the overall migration pattern (Strangler, Big Bang, Event Interception, etc.)?

☐ **P1** Have we chosen our approach to data migration and synchronization?

☐ **P1** Have we decided how to handle integration with systems that aren't being migrated?

☐ **P1** Have we established short feedback loops for early validation of migration approaches?

☐ **P1** Are we regularly providing business value through incremental delivery?

☐ **P1** Do we have a clear ownership model for components during transition and after migration?


### P2 - Important Follow-up Questions

☐ **P2** Have we decided on our approach to handling transitional states and dual-system operations?

☐ **P2** Have we chosen patterns for maintaining data consistency during migration?

☐ **P2** Have we decided on our testing and validation approach for migration increments?

☐ **P2** Can we implemented frequent releases to prove our ability to deliver quickly post-migration?

☐ **P2** Have we considered test automation that supports rapid, confident changes?

☐ **P2** Have we documented architectural decisions for future reference?

### P3 - Additional Considerations

☐ **P3** Have we decided on monitoring and observability approaches for the migration process?

☐ **P3** Have we chosen our approach to feature flags or configuration management during transition?

☐ **P3** Are we "building as we mean to continue" with the same practices we want post-migration?

*If the goal is to release every two weeks post-migration, start releasing every two weeks during migration.*

☐ **P3** Do we have a plan to eventually decommission any remaining legacy components?

☐ **P3** Have we designed our testing approach to validate that migrated functionality performs equivalently to legacy systems under real-world conditions?

*Beyond functional testing, ensure performance, reliability, and user experience match or exceed legacy system capabilities.*

> **Facilitator Note:** Focus on decisions that can't be easily changed later. Avoid getting bogged down in implementation details that can be refined during execution.

---

## ⚠️ Risks & Mitigation
*What could go wrong & how we'll handle it*

### P1 - Critical Workshop Questions

☐ **P1** Have we identified the top technical risks that could derail the migration?

☐ **P1** Have we identified business continuity risks during the migration process?

☐ **P1** Do we have data migration risks and verification strategies identified?

☐ **P1** Have we planned contingencies for our most critical dependencies?

☐ **P1** Have we identified potential resistance points among user groups?

☐ **P1** Have we avoided heavyweight change processes that contradict our future delivery goals?

### P2 - Important Follow-up Questions

☐ **P2** Do we have a plan to address fears about job security or role changes?

☐ **P2** Have we accounted for training needs for different user groups?

☐ **P2** Do we understand how daily workflows will change and how to support that transition?

☐ **P2** Have we prepared users and stakeholders for potential temporary disparities in user experience during phased migration?

*During incremental migration, users may experience different interfaces when moving between old and new system components.*

☐ **P2** Do we have champions in each business unit to help promote the change?

### P3 - Additional Considerations

☐ **P3** Have we communicated the benefits of the new system to all affected parties?

☐ **P3** Have we considered how to manage workload during the transition period?

☐ **P3** Have we addressed the organizational behaviors that led to the legacy situation in the first place?

*Consider what patterns of decision-making or organizational culture contributed to the legacy situation and how to change them.*

> **Facilitator Note:** Risk identification often reveals gaps in earlier analysis. Use risks to validate previous sections and identify areas needing more detailed planning.

---

## System Consolidation (if applicable)
*Special considerations when merging multiple legacy systems*

### P1 - Critical Workshop Questions

☐ **P1** Have we mapped feature parity requirements between the systems being consolidated?

☐ **P1** Do we understand the different user experiences and expectations for each system?

☐ **P1** Have we identified potential conflicts in business processes between systems?

☐ **P1** Do we have a strategy for data reconciliation between disparate systems?

### P2 - Important Follow-up Questions

☐ **P2** Have we established decision-making criteria for resolving conflicting requirements?

☐ **P2** Do we understand the organizational impacts of merging user communities?

☐ **P2** Have we documented terminology differences to ensure consistent understanding?

### P3 - Additional Considerations

☐ **P3** Have we re-evaluated the assumption that all systems need to be consolidated rather than some retired?

> **Facilitator Note:** System consolidation adds significant complexity. If applicable, ensure these questions get P1 attention as they fundamentally impact migration strategy.

---

## Post-Migration Success
*Ensuring we actually deliver the promised business value*

### P1 - Critical Workshop Questions

☐ **P1** Do we have a maintenance and support plan for the new system?

☐ **P1** Do we have data/metrics to measure the success of the migration?

☐ **P1** Do we have knowledge transfer plans to operational teams?

☐ **P1** Have we documented architectural decisions for future reference?

### P2 - Important Follow-up Questions

☐ **P2** Do we have plans to collect user feedback after implementation?

☐ **P2** Have we established a process for addressing issues and enhancements post-launch?

☐ **P2** Have we validated that the promised benefits (faster time to market, lower cost of change) are actually realized?

☐ **P2** Have we implemented continuous delivery practices that were promised in the business case?

☐ **P2** Have we scheduled a retrospective to capture lessons learned?

### P3 - Additional Considerations

☐ **P3** Have we established processes to ensure we don't accumulate technical debt in the new system?

☐ **P3** Do we have a plan to eventually decommission any remaining legacy components?

> **Facilitator Note:** Post-migration success is where many projects fail. Technical completion ≠ business success. Ensure the team commits to measuring and validating actual business outcomes.

---

## Workshop Summary & Next Steps

**Key Decisions Made:**
- _[To be filled during workshop]_

**Critical Risks Identified:**
- _[To be filled during workshop]_

**Immediate Follow-up Actions:**
- _[To be filled during workshop]_

**Important Follow-up Actions:**
- _[To be filled during workshop]_

**Future Considerations:**
- _[To be filled during workshop]_

---

*Legacy Migration Checklist v3.0 - Workshop Edition*  

