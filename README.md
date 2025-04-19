# Splunk-practice
My daily practice of Splunk 9.4.1 monitoring tool

installed at splunk.com

I just learned what Splunk's UI looks like. Seeing many buttons, dropdowns, and texts all on the same page 
it's kinda overwhelming at first, but the longer I tried to understand each feature, the more I began to understand how it's used.

I learned how to search effectively through the logs using indexing keywords and shortcuts.

Here is the sample log last night that I saw on my computer when it shut down unexpectedly (I searched this information using "EventType=1", which means error logs):

04/18/2025 10:57:26 PM

LogName=System

EventCode=41

EventType=1

ComputerName=REDACTED-PC

User=NOT_TRANSLATED

Sid=REDACTED-SID

SidType=0

SourceName=Microsoft-Windows-Kernel-Power

Type=Critical

RecordNumber=8844

Keywords=None

TaskCategory=63

OpCode=Info

Message=The system has rebooted without cleanly shutting down first. This error could be caused if the system stopped responding, crashed, or lost power unexpectedly.

host = REDACTED-PC source = WinEventLog:System sourcetype = WinEventLog:System

