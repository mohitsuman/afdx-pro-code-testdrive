# AFDX Pro-Code Testdrive

## Generate a new Agent Spec
```
sf agent generate agent-spec
```

## Delete an Agent and Related Metadata
```
sf project delete source -m Agent:My_First_Agent  
```

## Generate a new Agent Spec from an existing Agent Spec.
```
sf agent generate agent-spec --spec specs/Local_Info_Agent-partialAgentSpec.yaml 
```

## Create a new Agent using an Agent Spec.
```
sf agent create --preview --api-name Guest_Experience_Agent
```

## Deploy everything except Agents.
```
sf project deploy start --manifest manifests/EverythingExceptAgents.package.xml 
```
