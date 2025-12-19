# Agnt Cmp Name
- Agent
- Producer
- Broker
- Representative
- Retail Agent
- Surplus Agent

## Rules
- We can take agency details as per the document.
- If we get agency name along with agent name then we should take agent name.
- If we give multiple agency names are available we can take which one is more information.
- Agent information is first priority.
- If there is agency information is not available in the document we can take it as None Shown.

**We need at least 2 fields to take agency details**
- Agency name with Address and with Zip code
- Agency name with Phone number
- Agency name with Fax number
- Agency Address and Zip code

**None Shown**
- Only Agency name
- Only Agent name
- Agent name with zip code
- Only Agent phone number
- Only Agent Fax number

In the Fax page we can take agency details if the any of the agent details or matched in Fax page either phone number or address or agency name.



