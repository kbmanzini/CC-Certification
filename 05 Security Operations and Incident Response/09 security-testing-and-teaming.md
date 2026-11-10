# Security Testing and Teaming

## 1. What Is Security Testing?

Security testing evaluates whether systems, applications, networks, and processes have weaknesses that could affect security.

It helps organizations identify problems before they cause harm.

Testing must be authorized and performed within an approved scope.

## 2. Vulnerability Scanning

Vulnerability scanning uses tools to identify known security weaknesses.

It may identify:
- Missing security updates
- Unsupported software
- Insecure configurations
- Known vulnerable versions
- Unexpected open services

A scan identifies possible weaknesses but does not always prove that a weakness can be exploited.

## 3. Vulnerability Assessment vs. Penetration Testing

| Vulnerability assessment | Penetration testing |
|---|---|
| Identifies and evaluates weaknesses | Tests security under an authorized, defined scope |
| Often uses automated scanning | May combine manual analysis and specialized tools |
| Focuses on finding and prioritizing weaknesses | Evaluates whether weaknesses could lead to meaningful impact |

Both should be conducted with proper authorization.

## 4. Static Application Security Testing (SAST)

SAST examines application source code or compiled code without running the application.

It can help identify:
- Potential coding weaknesses
- Insecure coding patterns
- Certain input-handling problems
- Possible data exposure issues

SAST is often called a white-box testing approach because it can examine the application's internal code.

## 5. Dynamic Application Security Testing (DAST)

DAST examines a running application from the outside.

It looks for weaknesses in the application's behavior while it is operating.

SAST vs. DAST:

| SAST | DAST |
|---|---|
| Examines code without running the application | Tests a running application |
| Looks at internal code | Looks at application behavior |
| Often used during development | Often used against a running test environment |

## 6. Threat Modeling

Threat modeling is a structured process for identifying potential threats and weaknesses during system design or review.

A simplified process:

1. Identify important assets.
2. Understand the system and its components.
3. Identify possible threats.
4. Evaluate weaknesses and potential impacts.
5. Select appropriate safeguards.
6. Review the model as the system changes.

Threat modeling encourages security to be considered early.

## 7. Red, Blue, and Purple Teams

### Red Team
A red team performs authorized adversarial assessments to evaluate an organization's defenses.

### Blue Team
A blue team focuses on defending systems, detecting suspicious activity, and responding to threats.

### Purple Team
A purple team approach encourages red and blue teams to work together and improve security through collaboration.

| Team | Main focus |
|---|---|
| Red | Evaluate defenses from an adversarial perspective |
| Blue | Defend, detect, and respond |
| Purple | Improve collaboration and defensive effectiveness |

## 8. Physical Security Testing

Physical security testing evaluates whether physical safeguards are effective.

Areas that may be reviewed:
- Building access procedures
- Visitor management
- Badge systems
- Security cameras
- Doors and restricted areas
- Equipment protection

Any physical assessment must have explicit authorization, a defined scope, and safety procedures.

## 9. Security Audits

A security audit is a structured review of security controls, policies, procedures, or compliance requirements.

Audits may examine:
- Access permissions
- Security documentation
- Configuration standards
- Logging practices
- Backup procedures
- Policy compliance

## 10. Remediation and Retesting

Finding a weakness is only part of the process.

Organizations should:
1. Document the finding.
2. Evaluate its severity and impact.
3. Assign responsibility.
4. Apply an appropriate fix or mitigation.
5. Retest to confirm the issue was addressed.
6. Record the result.

## Key Takeaways

- Vulnerability scanning identifies possible weaknesses.
- Penetration testing evaluates security within an authorized scope.
- SAST examines code without running the application.
- DAST examines a running application.
- Threat modeling identifies potential threats during design and review.
- Red teams evaluate defenses; blue teams defend; purple teams improve collaboration.
- Retesting helps confirm that remediation worked.