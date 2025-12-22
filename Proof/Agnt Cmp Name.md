# Agnt Cmp Name
- Agent
- Producer
- Broker
- Representative
- Retail Agent
- Surplus Agent

## Rules

Key agent information when 2 or more of the fields are available.

Agent information can only be entered if we have the following Information available

**We need at least 2 fields to take agency details**
1. Agency name + Address + Zip code
2. Agency name + Phone number
3. Agency name + Fax number
4. Agency Address + Zip code + Phone or Fax number

When we have both agency name and agent name in the document we should capture the 'agent name' for agent comp name.
- If we get agency name along with agent name then we should take agent name.

When document has Agency and broker information we should give the priority for whichever is having more information. If both have same information first priority will be agency.


- If there is agency information is not available in the document we can take it as None Shown.

**None Shown**

Key agent as **None Shown** when there is no agent information at all or only 1 piece of information is available out of the Agent Name, Agency Address or Agent Phone number.
- Only Agency name
- Only Agent name
- Agent name with zip code
- Only Agent phone number
- Only Agent Fax number

If only the Agent name is listed, without an address and/or phone number, then key agent info as **NONE SHOWN**.

In the Fax page we can take agency details if the any of the agent details or matched in Fax page either phone number or address or agency name.

## Examples

Insurance agency DBA Stephen

Insurance agency C/O Stephen

Here we can take agent name Stephen as agent name.


