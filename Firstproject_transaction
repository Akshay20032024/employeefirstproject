import Employee from 0x05

transaction(name: String, address: String, salary:Int,dob:Int,account:Address) {

    prepare(signer: AuthAccount) {}

    execute {
        Employee.addata(name:name, address: address,salary:salary,dob:dob,account:account) 
        log("Thank You.")
    }
}
