# Adjust-SubView-Frame-to-adjust-according-to-mainView-Frame-And-Constraint
This code will help to add subView to mainView According to the mainView Frames and Constraint to properly fit into mainView



`

    //Variables Declaration
    var fitSubViewToMainViewFrame:CGRect!

    override func viewDidLayoutSubviews() {
        super.viewDidLayoutSubviews()
        
        //Frame Size to fit subview into the mainview according to the screen sizes
        fitSubViewToMainViewFrame = CGRect(x: 0, y: 0, width: mainView.frame.width, height: mainView.frame.height)
        
        print("Mainview height", mainView.frame.height)
    }
    
 `
