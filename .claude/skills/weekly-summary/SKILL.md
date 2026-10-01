---
name: weekly-summary
description: Generate a comprehensive weekly study summary
---

# AWS Certified Generative AI Developer - Professional Weekly Study Summary Generator

## Purpose

Generate a comprehensive weekly study summary for AWS Certified Generative AI Developer - Professional exam preparation by analyzing multiple daily session files.

## Input Requirements

You will be provided with:

- The start date for the week (e.g., 2025-09-15)
- Multiple session files from the `sessions/` directory spanning a week
- Session files follow naming pattern: `YYYY-MM-DDTHH-MM-SS.md`
- Each session contains practice questions, answers, and performance tracking

## Output Structure

Create a markdown file in `summary/` directory with timestamp: `YYYY-MM-DDTHH-MM-SS-weekly-summary.md`

### Required Sections

#### Header with Key Metrics

```markdown
# AWS Certified Generative AI Developer - Professional Weekly Study Summary: [Date Range]

**Study Period:** [Start Date] - [End Date]
**Total Sessions:** [Number]
**Total Questions:** [Number]
**Overall Weekly Performance:** [Correct]/[Total] ([Percentage]%)
```

#### Daily Performance Breakdown

For each session, include:

- **Day of week and date**
- **Session Duration** (if available)
- **Performance:** X/Y (percentage) with visual indicators
- **Topics Covered:** List of main exam topics
- **Key Learning/Miss:** Most significant insight or error
- Use ⭐ for best session, ⚠️ for most challenging

#### Knowledge Progression Analysis

Categorize topics into three performance tiers:

**🔥 Mastered Topics (Consistent Success)**

- Topics with 80%+ success rate across sessions
- Include specific technical understanding demonstrated
- Note consistent patterns of correct answers

**⚠️ Inconsistent Performance (Mixed Results)**

- Topics with 40-79% success rate
- Identify what works vs. what doesn't
- Note specific knowledge gaps within the topic

**❌ Critical Knowledge Gaps (Consistent Weakness)**

- Topics with <40% success rate
- Mark as critical if affects major exam sections

#### Exam Section Performance Analysis

Map performance to the six exam sections:

- Section 1: Design Applications
- Section 2: Data Preparation
- Section 3: Application Development
- Section 4: Assembling and Deploying Applications
- Section 5: Governance
- Section 6: Evaluation and Monitoring

For each section:

- Calculate performance percentage
- Use ✅ (>70%), ⚠️ (50-70%), ❌ (<50%)
- List strengths and gaps
- Note if critical for exam success

#### Weekly Learning Achievements

Document concrete progress:

**🎯 Key Technical Insights Gained**

- List 3-5 major technical concepts mastered
- Include specific AWS services or patterns

**📈 Notable Improvements**

- Topics that showed improvement over the week
- Learning trajectory observations

**📉 Persistent Challenges**

- Topics that remained difficult
- Recurring error patterns

#### Priority Study Plan for Next Week

Create actionable study plan:

**🚨 Critical Gap Remediation (X% of time)**

- Focus on lowest-performing sections
- Specific resources and approaches
- Hands-on practice recommendations

**📚 Knowledge Solidification (X% of time)**

- Reinforce inconsistent topics
- Practice question focus areas

#### Exam Readiness Assessment

Provide honest assessment:

**✅ Ready for Exam (Current Strengths)**

- Topics with 80%+ confidence
- Confidence percentages

**⚠️ Approaching Readiness (Needs Work)**

- Topics with 60-79% confidence

**❌ Not Ready (Critical Gaps)**

- Topics with <60% confidence
- Mark blocking issues

**🎯 Current Exam Prediction**

- Estimated score range (need 70% to pass)
- Gap analysis
- Time to readiness estimate

#### Recommended Study Resources

Organize by priority:

**📖 High-Priority Reading**

- AWS whitepapers and documentation
- Specific to identified gaps

**🛠 Hands-On Practice**

- Lab exercises for weak areas
- Service-specific practice

**📊 Progress Tracking**

- Metrics to monitor
- Review schedule

#### Conclusion

Provide:

- Overall trajectory assessment
- Key blocker identification
- Confidence and timeline estimate
- Motivational but realistic outlook

## Analysis Instructions

### Performance Calculation

- Count total correct answers across all sessions
- Calculate section-specific performance
- Track improvement trends day-over-day
- Identify consistent vs. inconsistent performance patterns

### Gap Identification

- Mark any section with <50% as critical
- Prioritize sections by exam weight and current performance

### Learning Pattern Recognition

- Look for topics that improved or declined over the week
- Note recurring mistakes or confusion patterns
- Identify successful learning approaches

### Study Plan Prioritization

- Allocate 60% time to critical gaps (sections <50%)
- Allocate 30% to inconsistent areas (50-79%)
- Allocate 10% to strengths maintenance (>80%)

### AWS Knowledge Integration

- Use MCP AWS documentation tools to validate technical explanations
- Reference current AWS best practices and patterns
- Ensure recommendations align with exam blueprint

## Quality Standards

### Technical Accuracy

- All AWS service explanations must be current and accurate
- Domain weightings must match official AIP-C01 exam guide
- Study resources must be relevant to identified gaps

### Actionability

- Every recommendation must be specific and actionable
- Time allocations must be realistic and measurable
- Study plans must include concrete resources and approaches

### Motivation and Realism

- Maintain encouraging tone while being honest about gaps
- Provide realistic timelines for exam readiness
- Celebrate genuine progress and achievements

### Structure and Readability

- Use consistent markdown formatting
- Include visual indicators (✅, ⚠️, ❌, 🔥, 📈, etc.)
- Maintain clear section hierarchy
- Ensure scannable format for quick reference

## Example Performance Indicators

- ✅ **STRONG** (80%+)
- ⚠️ **MODERATE** (50-79%)
- ❌ **CRITICAL GAP** (<50%)
- 🔥 **MASTERED** (consistent success)
- ⭐ **Best Session**
- ⚠️ **Most Challenging**

## Success Metrics

A good weekly summary should:

1. Accurately reflect the week's study performance
2. Identify the top 3 priority areas for improvement
3. Provide actionable study plan for the following week
4. Give realistic assessment of exam readiness
5. Motivate continued study while highlighting critical gaps
