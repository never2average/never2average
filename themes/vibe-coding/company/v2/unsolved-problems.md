# Unsolved Problems

Cabinet is still just a concept. Nothing big has been built yet.

The first blocker is that Relay itself has not been proven as a 26-week playbook. Cabinet depends on Relay working. If the playbook cannot reliably take Thin Wedge toward a generally available product launch, Cabinet has no foundation.

The second blocker is agent-readable company state. Cabinet has to store the company in a way that agents can use without hallucinating authority or flattening the company into a rigid project-management tool.

The third blocker is eval wiring. If Cabinet is triggering agents and moving the roadmap, it needs to know whether those actions are actually making the company better. Busy work is a failure mode.

The fourth blocker is human-agent handoff quality. Cabinet has to coordinate agents, but also humans: the GTM person, developer, senior SRE, implementation engineer, and founder. The system has to know when work moves from an agent to a person, and what context must travel with it.

The fifth blocker is permissions. The founder can delegate narrow authority, but the system has to preserve who can approve what. A company runtime that blurs authority becomes dangerous very quickly.

The scariest failure mode is founder-mode state inspection. If the founder has to open the underlying company state, edit it by hand, and then hope the system resumes correctly, that is the boundary where Cabinet can break. Resuming from edited company state has to be treated as a serious design problem, not an edge case.

Cabinet works when the company is running automatically, making money, and depositing it into the founder's bank account, while the founder still owns the final decisions.
