# Set Up Proactive Governance Guardrails using CloudFormation Hooks

### Goal:
- Set Up Proactive Governance Guardrails across an Organization

### Set Up CFN CLI
```
pip install cloudformation-cli cloudformation-cli-python-plugin
```
### Initialize Hook

```
(base) (.venv) TR-C02YWAPBLVCG:proactive-gov-guardrails paushali.kundu$ cfn init
Initializing new project
Do you want to develop a new resource(r) or a module(m) or a hook(h)?.
>> h
What's the name of your hook type?
(Organization::Service::Hook)
>> paushalisb::cloudfrontdistributionminimumprotocolversion::Hook
Select a language for code generation:
[1] python36
[2] python37
(enter an integer): 
>> 2
Use docker for platform-independent packaging (Y/n)?
This is highly recommended unless you are experienced 
with cross-platform Python packaging.
>> n
Initialized a new project in /Users/paushali.kundu/OneDrive - Thomson Reuters Incorporated/My Documents/proactive-gov-guardrails
```

