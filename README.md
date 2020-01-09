# luzling_back
Luzling backend
API - https://drive.google.com/open?id=169OpPBtVgYbzYP4ruodrIEbCKuADLLJ9s-dwP2ePYlE
## API

* getAllPackages() -> [package]
* createRoom(name, package) -> roomId 
* getAllRooms() -> ArrayList[roomId]
* joinRoom(int roomId, userName) -> {userId, package}
* startGame(roomId) -> startedUser
* chooseQuestion(questionId) -> Question
* notifyQuestionReceived(questionId)
* submitQuestion()
* answer(answer) -> rightOrNot
* nextRound(packageId, currentRound)
* leaveRoom(roomId)

Need to keep users and their current scores
