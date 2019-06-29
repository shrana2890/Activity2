Student id: C0736516
Student name: Sukhwinder


Question: On the IOS side, what function is used to receive messages from the watch?
Answer:
func session(_ session: WCSession, didReceiveMessage message: [String : Any], replyHandler: @escaping ([String : Any]) -> Void) {
<#code#>
}

=> basically we get data on each side from massage Dictionary.

Question: When receiving messages from the watch, you need to use a closure function. What is the reason why a closure is used?
Answer: Because by using closure function we can still acess or get local variable's value even after exiting that fuction as after exiting function local variable no longer exists. closure function keeps reference of local variables and we can then use that local variables. 
