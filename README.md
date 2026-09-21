Quantum Measurement

Separating the Physical Burdens and Testing Outcome-Conditioned Continuation

DOI: https://doi.org/10.5281/zenodo.22879295

This repository contains one coordinated Structural Flow publication package centered on the scientific artifact Quantum Measurement: Separating the Physical Burdens and Testing Outcome-Conditioned Continuation.

The work does not treat “the measurement problem” as one undifferentiated question. It separates several physical and theoretical burdens that can fail independently, then develops the Quantum Continuation Closure Test (QCCT) as an experimentally answerable test of outcome-conditioned continuation.

The present release is pre-result. It does not claim that standard quantum mechanics has failed, that a generalized state-update rule has been observed, or that the Born rule has been derived.

Package map

1. Primary scientific artifact

Quantum_Measurement_Anchor_Artifact_v1.0.pdf

Quantum_Measurement_Anchor_Artifact_v1.0.txt

The anchor artifact owns the scientific argument. It separates the relevant measurement burdens, develops QCCT, explains the ordinary-quantum comparison class, situates the proposal relative to prior measurement literature, and states the bounded conclusions that different experimental outcomes can support.

2. QCCT Audit and Execution Companion

Quantum_Measurement_QCCT_Audit_and_Execution_Companion_v1.5.txt

This is the operating manual for the QCCT scientific program.

It contains:

QCCT-I entry procedures;

comparator ordering;

STOP rules;

optional modules;

existing-data entry;

distributed partial closure;

result-transfer rules;

canonical equations;

machine-audit instructions;

return templates;

verdict language.

The companion does not replace the anchor's scientific argument and does not enlarge the claims encoded by the machine files.

3. Consolidated Quantum Measurement contracts and adapters

SF_Quantum_Measurement_Contracts_and_Adapters_v1_0.lean

This Lean file contains two scientifically distinct machine modules under one public file:

Seam G — Born weighting / quantum probability measure

QCCT-I — preparation-indistinguishability / outcome-conditioned continuation

They remain separate contracts and adapters in separate namespaces.

Consolidation changes packaging only. It does not merge their scientific objects, burdens, evidence states, dispositions, or claims.

The QCCT execution procedures in the companion concern the QCCT-I experimental program.

The presence of Seam G in the same Lean file does not make Seam G part of the QCCT-I empirical burden.

4. Structural Flow Universal Kernel

Structural_Flow_Universal_Kernel_v1.0.lean

This is the exact frozen public Universal Kernel used beneath the Quantum Measurement contracts and adapters.

The Universal Kernel is unchanged by this release.

The machine dependency is:

Universal Kernel → consolidated Quantum Measurement contracts and adapters

Scientific target

QCCT-I asks a narrow physical question:

If two physically different proper-mixture preparation procedures are represented by the same admitted standard quantum input, does nature erase that preparation difference from the statistics of what happens after the same measurement outcome?

The canonical preparation pair is:

a randomized Z-basis proper mixture;

a randomized X-basis proper mixture;

with both represented by the same maximally mixed qubit state under the admitted standard quantum description.

A stronger preparation-indistinguishability verdict is available only after the experiment has separately discharged the relevant entry and comparator burdens.

Ordinary quantum physics gets first refusal

A deviation from an ideal Lüders prediction is not, by itself, evidence for new physics.

QCCT therefore gives ordinary explanations their own registered seats before a generalized continuation rule earns attention.

These include, as applicable:

preparation mismatch;

improper-mixture / Gemenge mismatch;

calibration failure;

different first-measurement seats;

preparation side channels;

an ordinary non-Lüders quantum instrument;

finite-horizon process memory;

an independently warranted expanded physical reference.

Only after the admitted ordinary comparison architecture has been lawfully tested may a stronger preparation-indistinguishability claim be considered.

Machine dispositions

The consolidated Lean file contains two scientifically distinct modules.

Their generic public dispositions remain:

NOT YET ADJUDICABLE

They remain not yet adjudicable for different reasons.

For Seam G, domain-owned probability-admission burdens remain open.

For QCCT-I, real empirical burdens remain open, including the required preparation, reference, measurement, side-channel, comparator, and adjudication burdens.

An open domain or empirical requirement is not a machine contradiction.

What a clean machine run establishes

A clean Lean elaboration establishes that the encoded machine contracts and adapters coexist coherently beneath the compatible Universal Kernel used for the run.

For QCCT-I, the encoded architecture preserves distinctions including:

proper Gemenge is not the same object as an improper mixture;

fixed standard instrument is not the same comparator as a finite-horizon process tensor;

preparation side channels remain explicit;

fixed-instrument and process-tensor comparators remain ordered rather than collapsed;

reference expansion remains a separate route;

bounded verdicts and existing-data boundaries remain represented;

distributed partial closure remains scoped;

real empirical admission remains open.

The machine result audits the encoded architecture of the question.

The experiment governs the physical answer.

What a clean machine run does not establish

A clean run does not establish that:

the canonical preparations were physically realized;

the preparations are genuine proper mixtures;

the preparations are operationally equivalent at the declared reference;

the required first measurement has been physically admitted;

the same physical measurement instrument acted on both branches;

preparation side channels are closed;

a fixed quantum instrument fails;

a finite-horizon process tensor fails;

the Fiorentino–Weigert family is physically realized;

an anomaly has been observed;

standard quantum mechanics has failed;

any interpretation of quantum measurement has been established;

the Born rule has been derived.

The Lean file also does not replace the scientific derivation of the QCCT witness equations.

Reproducing the release-machine checkpoint

Preserve these files unchanged:

Structural_Flow_Universal_Kernel_v1.0.lean

SHA-256:

b455ec869d062f0fc05d239c5006c843165cd598edbd8c35eae442ff471689a3

SF_Quantum_Measurement_Contracts_and_Adapters_v1_0.lean

SHA-256:

4fd18d9f11c469d192a6351adad0c033a1efcbcdd35b5ce0ba5b5580f67f08e7

To reproduce the public machine checkpoint:

Place the exact unchanged Universal Kernel first.

Append the entire consolidated Quantum Measurement contracts-and-adapters file directly beneath it.

Do not insert an import line between them.

Elaborate the combined source.

For this release, the consolidated Quantum Measurement file was appended beneath the unchanged compatible Universal Kernel and elaborated cleanly twice during the release audit.

Frozen release hashes

Primary artifact source SHA-256:

048d0e3b31bbcca58af33b1b36ef69c0143f9108e326d9094ea19def2b02b624

Audit and Execution Companion SHA-256:

6adf859b20bf5c152ddc1e76bc9e31c8f847c0b57af3ba6f82eb9a9e3af0ae71

Quantum Measurement contracts and adapters SHA-256:

4fd18d9f11c469d192a6351adad0c033a1efcbcdd35b5ce0ba5b5580f67f08e7

Universal Kernel SHA-256:

b455ec869d062f0fc05d239c5006c843165cd598edbd8c35eae442ff471689a3

AI-assisted preparation

During the preparation and revision of the manuscript and its accompanying formal materials, generative AI tools were used for drafting support, language refinement, structural editing, experimental-design organization, formalization support, machine-audit organization, consistency checking, and clarity.

All substantive arguments, scientific claims, experimental-design choices, formalization choices, scope decisions, and final editorial judgments remain the author's own responsibility.

Citation

Quantum Measurement: Separating the Physical Burdens and Testing Outcome-Conditioned Continuation.

DOI: https://doi.org/10.5281/zenodo.22879295
