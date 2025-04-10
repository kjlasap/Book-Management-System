class Book {
    // Attributes
    private String title;
    private String author;
    private double price;

    // Default Constructor
    public Book() {
        this.title = "Unknown";
        this.author = "Unknown";
        this.price = 0.0;
    }

    // Parameterized Constructor
    public Book(String title, String author, double price) {
        this.title = title;
        this.author = author;
        this.price = price;
    }

    // Copy Constructor
    public Book(Book anotherBook) {
        this.title = anotherBook.title;
        this.author = anotherBook.author;
        this.price = anotherBook.price;
    }

    // Method to display book details
    public void displayBook() {
        System.out.println("Title: " + this.title);
        System.out.println("Author: " + this.author);
        System.out.println("Price: " + this.price);
    }
}

public class BookManagementSystem {
    public static void main(String[] args) {
        // Creating a book using the default constructor
        Book defaultBook = new Book();
        System.out.println("Default Book:");
        defaultBook.displayBook();
        System.out.println();

        // Creating a book using the parameterized constructor
        Book parameterizedBook = new Book("Java Programming", "John Doe", 500.0);
        System.out.println("Parameterized Book:");
        parameterizedBook.displayBook();
        System.out.println();

        // Creating a book using the copy constructor
        Book copiedBook = new Book(parameterizedBook);
        System.out.println("Copied Book:");
        copiedBook.displayBook();
    }
}
