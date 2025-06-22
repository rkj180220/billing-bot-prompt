# AI-Powered Customer Support Assistant for Billing Queries

## Project Overview
Develop an enhanced AI customer support assistant specifically designed to handle billing-related queries for a SaaS product. The current basic prompt lacks specificity and produces generic responses that don't adequately address complex billing scenarios.

## Current Problem
**Existing Prompt:** "You are a helpful assistant. Answer the user's question about their billing issue."

**Issues Identified:**
- Too generic and lacks context
- No specific domain knowledge
- Missing security considerations
- No structured approach to complex billing scenarios
- Lacks clear guidelines for handling sensitive information

## Task Requirements

### 1. Prompt Analysis
- [ ] Identify specific weaknesses in the current prompt
- [ ] Document what makes billing support unique compared to general support
- [ ] Analyze security and compliance requirements for billing data

### 2. Refined Prompt Development
- [ ] Apply CLEAR framework (Context, Length, Examples, Audience, Role)
- [ ] Implement specificity and constraints
- [ ] Include security best practices
- [ ] Add domain-specific knowledge requirements
- [ ] Define clear boundaries and escalation paths

### 3. Chain-of-Thought Enhancement
- [ ] Develop CoT prompting for complex scenarios:
  - Late fee calculations and disputes
  - Refund eligibility determination
  - Incorrect charge investigations
  - Plan upgrade/downgrade billing impacts
- [ ] Structure step-by-step reasoning process
- [ ] Include decision trees for common scenarios

### 4. Testing and Validation
- [ ] Create sample billing scenarios for testing
- [ ] Generate responses using both prompts
- [ ] Compare effectiveness and accuracy
- [ ] Document performance differences

### 5. Deliverables
- [ ] **Refined prompt** with detailed specifications
- [ ] **CoT-enhanced prompt** with reasoning frameworks
- [ ] **Sample responses** for both approaches
- [ ] **Comparative analysis** with recommendations
- [ ] **Implementation guide** for deployment

## Acceptance Criteria
1. Prompts must handle sensitive billing information securely
2. Responses should be accurate, helpful, and professional
3. Complex scenarios should include clear reasoning steps
4. System should know when to escalate to human agents
5. All prompts must be well-documented and maintainable

## Success Metrics
- Response accuracy for billing queries
- Customer satisfaction with explanations
- Reduction in escalations to human agents
- Compliance with data protection requirements

## Implementation Timeline
- Analysis and research: 1-2 days
- Prompt development: 2-3 days
- Testing and refinement: 1-2 days
- Documentation: 1 day

## Technical Considerations
- Integration with billing system APIs
- Security protocols for handling payment information
- Audit logging for billing-related interactions
- Multi-language support considerations
