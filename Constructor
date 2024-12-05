// Class to represent a Customer
public class Customer {
    private int id;
    private String name;
    private String email;

    // Default constructor
    public Customer() {
        this.id = 0;
        this.name = "Unknown";
        this.email = "Not Provided";
    }

    // Parameterized constructor
    public Customer(int id, String name, String email) {
        this.id = id;
        this.name = name;
        this.email = email;
    }

    // Method to display customer details
    public void displayCustomerInfo() {
        System.out.println("Customer ID: " + id);
        System.out.println("Customer Name: " + name);
        System.out.println("Customer Email: " + email);
        System.out.println("-----------------------");
    }

    // Main method to demonstrate usage
    public static void main(String[] args) {
        // Creating a customer using the default constructor
        Customer defaultCustomer = new Customer();
        System.out.println("Default Customer:");
        defaultCustomer.displayCustomerInfo();

        // Creating customers using the parameterized constructor
        Customer customer1 = new Customer(101, "Alice", "alice@example.com");
        Customer customer2 = new Customer(102, "Bob", "bob@example.com");

        System.out.println("Parameterized Customers:");
        customer1.displayCustomerInfo();
        customer2.displayCustomerInfo();
    }
}
