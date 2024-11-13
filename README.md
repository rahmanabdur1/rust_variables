fn main() {
    let x = 29;

    let x = 45 + 5;

    {
        let x = x * 20;
        println!("The value of x in the inner scope is: {x}");
    }
    println!("The value of x is: {x}")
}
