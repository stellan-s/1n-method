# Summary (One Page)

The 1..n Method is a way to decide what to build, what not to build, and how to judge progress.

Its core idea is simple: **replace, don't accumulate**. Teams work on a small active set, and new work enters only by displacing current work.

## Core Principles

1. Development always has friction. You can reduce it, not remove it.
2. Time and attention are limited and must be protected.
3. Every extra active item increases friction.
4. Prioritization is only reliable in the near term.
5. **1..n** is the small set we commit to now; one item is most important.
6. Beyond 1..n is a **cognitive horizon**: visible, but not committed.
7. Only 1..n is **operationally binding**.
8. Outside the cognitive horizon, work should be **inert**.
9. Leadership must choose and say no.

## Decision Flow

```mermaid
flowchart TD
    A[New request or issue] --> B{What kind of request?}

    B -->|External request| C{Focus set full?}
    C -->|No| D{Commit now?}
    D -->|Yes| DA[Put in Focus set]
    D -->|No| DB[Not chosen, no commitment]
    C -->|Yes| E{More important than current focus?}
    E -->|Yes| F[Replace a Focus item]
    E -->|No| G[Not chosen, no commitment]
    G --> H[Explain: new work needs replacement]
    DB --> H

    B -->|Cannot explain importance| I{Clear enough to compare?}
    I -->|Yes| J[Clarify it so we can compare]
    I -->|No| K[Not ready, keep out of Focus set]

    B -->|Needs preparation| L[Do prep to understand]
    L --> M[No tasks, estimates, or commitments]

    B -->|Small fix, typo, cosmetic| N{Below decision threshold?}
    N -->|Yes| O[Fix directly]
    N -->|No| P[Handle through Focus set]

    B -->|What about ideas?| Q[Ideas are welcome]
    Q --> R[Only Focus set is binding]
    R --> S[Outside horizon stays inert]

    B -->|Important but never fits| T[Diagnostic signal]
    T --> U[Need is bigger than capacity]
    U --> V[Leadership must act]

    B -->|Leadership asks for metrics| W[Measure reality, not activity]
    W --> X[Check production fitness]
    X --> Y[Missing key features = low quality]

    B -->|Must we always build?| Z[No]
    Z --> AA[Build only to close a quality gap]

    DA --> END[Clear outcome]
    F --> END
    H --> END
    J --> END
    K --> END
    M --> END
    O --> END
    P --> END
    S --> END
    V --> END
    Y --> END
    AA --> END
```

## Key Terms

- **1..n / Focus set:** The small active set (usually 1-3 items).
- **Inert:** Work that exists but is not active, prioritized, or promised.
- **Replacement:** New work enters only by displacing current focus.
- **Fitness for purpose:** Success in production for real users.

Version: **1.1.0**
