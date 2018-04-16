# SecOpsKata

SecOpsKata is a framework for training & testing security professionals and the tools they're using.  It attempts to ensure that for the whole security chain from unauthorised event to (potentially) triage by a human, results are consistent in detecting breaches of systems accounts or data.

To carry it out there are several components:
- agents to initiate events which should be detected as malicious or non-malicious
- intermediary configuration to either use common security platforms in a way the tests can be properly instrumented in SIEM/IDS/other security controls, or simulate it.
- means to verify the reslts of workflow and ensure malicious and non-malicious tests resulted in the correct results.

The aim is that these tools can actually be used in security operations team training and hiring practices, but also as full-system tests, potentially even in real environments. 

This is intended to build resilience and reliability in security operations both from a human and technical standpoint, under similar approached to how Netflix's https://github.com/Netflix/SimianArmy/wiki/Chaos-Monkey project forces verification of the resilience of production systems. 

