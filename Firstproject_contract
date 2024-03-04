pub contract Employee {
    pub var datasheets:{Address: data}
    
    pub struct data
    {
        pub let name:String
        pub let address:String
        pub let salary:Int
        pub let dob:Int
        pub let account: Address
        
        init(_name: String, address: String, _salary:Int, _dob:Int,_account: Address) 
        {
            self.name = _name
            self.address =address
            self.salary = _salary
            self.dob = _dob
            self.account=_account
        }
    }

    pub fun addata(name: String, address: String,salary:Int,dob:Int,account:Address) 
    {
        let newdata = data(_name: name, address:address, _salary:salary, _dob:dob,_account:account)
        self.datasheets[account] =newdata
    }

    init() 
    {
        self.datasheets = {}
    }





 

}
