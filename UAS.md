Question  below are based on the trace file tcp-ethereal-trace-1 in in http://gaia.cs.umass.edu/wireshark-labs/wireshark-traces.zip

Answer the following questions for the TCP segments:

1.	What is the IP address and TCP port number used by your client computer (source) to transfer the file to gaia.cs.umass.edu?
2.	What does gaia.cs.umass.edu use the IP address and port number to receive the file. (Attach the screenshot of your Wireshark's display).
3.	What is the sequence number of the TCP SYN segment that is used to initiate the TCP connection between the client computer and gaia.cs.umass.edu?
    What is it in the segment that identifies the segment as a SYN segment? (Attach the screenshot of your Wireshark's display).
4.	What is the sequence number of the SYNACK segment sent by gaia.cs.umass.edu to the client computer in reply to the SYN?
    What is the value of the ACKnowledgement field in the SYNACK segment? How did gaia.cs.umass.edu determine that value?
  	What is it in the segment that identifies the segment as a SYNACK segment? (Attach the screenshot of your Wireshark's display).
5.  What is the sequence number of the TCP segment containing the HTTP POST command? Note that in order to find the POST command,
    you’ll need to dig into the packet content field at the bottom of the Wireshark window, looking for a segment with a “POST” within its DATA field.
    (Attach the screenshot of your Wireshark's display).
6.	Consider the TCP segment containing the HTTP POST as the first segment in the TCP connection. What are the sequence numbers of the first six TCP connection segments
    (including the HTTP POST segment)? At what time was each segment sent? When was the ACK for each segment received? Given the difference between when each TCP segment was sent,
  	 and when its acknowledgement was received, what is the RTT value for each of the six segments? What is the EstimatedRTT value (see page 237 in textbook) after the receipt
  	 of each ACK? Assume that the value of the EstimatedRTT is equal to the measured RTT for the first segment, and then is computed using the EstimatedRTT equation on page 237 for all subsequent 
     segments. 
     Note: Wireshark has a nice feature that allows you to plot the RTT for each of the TCP segments sent. Select a TCP segment in the “listing of captured packets” window that is being sent from 
     the client to the gaia.cs.umass.edu server. Then select: Statistics->TCP Stream Graph-
     >Round Trip Time Graph
7.	What is the length of each of the first six TCP segments?(Attach the screenshot of your Wireshark's display).

   # ANSWERS 

   *Answer.1*
    IP address and TCP port numbers of the client computer (source).
    Source IP Address          : 192.168.110.37
    Source Port                     : 60662

   
   [Answer1](Picture1.png)
   
   
   


