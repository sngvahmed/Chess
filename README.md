Chess Viewer send data to Controller and Controller send the data to Parser Then send to Controller 
Controller send the Parser data to Query to create Query and Back to Controller then Controller send the 
data to ChessContext .
Chess Context sent the Query to DataHandler which is parse the data and CheckMoves check is its move is valid 
and then start to checks the moves by ChessPicesImplementation and sent the data to ChessContext
and chessContext send the data to DataHandler then back to chessContext.
chess context send the DataHandler to ChessManager.
ChessManager sent the Data to Query to Create Query and then Query Sent to user Viewer.


Notes i Know that Query Object Should not be sent Viewer but i am not understand this point 
