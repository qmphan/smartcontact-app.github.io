---
Title: Vxml CallQueue Object
---

## Introduction

Use this object to put the call into a queue.

## Object Parameters

classid: callqueue

Parameters:
  - queue_alias: Alias of the queue to route call to
  - greeting_message: ID of the greeting message to play. This will override the default greeting message of the queue.
  - waiting_music: ID of the sound entry to be used for waiting music. I.e the music the caller will hear while waiting for an agent to answer the call.
  - moh: ID of the sound entry to be used for music on hold. I.e the music the peer will hear while being put on hold by an agent. 
  - main_agent: email or alias of main agent who will handle the call. This parameter can appear multiple times to include multiple main agents.
  - backup_agent: email or alias of backup agent. This parameter can appear multiple times to include multiple backup agents.
  
Example:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<vxml>
    <form>
        <object name="queue" classid="call_queue">
            <param name="queue_alias" value="standard"/>
            <param name="greeting_message" value="@default_welcome"/>
            <param name="waiting_music" value="@default_music"/>
            <param name="main_agent" value="agent1"/>
            <param name="main_agent" value="agent2"/>
            <param name="backup_agent" value="agent3"/>
            <param name="backup_agent" value="agent4"/>
        </object>
    </form>
</vxml>
```
