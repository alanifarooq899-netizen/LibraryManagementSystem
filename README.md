# LibraryManagementSystem
This is my first Java project I made and it has to due with two data structures that are arrays and strings. Strings hold text data: Every book title's, ISBN, Author are string variable. 

package libraryManagementSystem;

public class Book {
	private String title;
	private String author;
	private String isbn;
	private boolean isAvailable;
	
	public Book(String title, String author, String isbn, boolean isAvailable) {
		this.title = title;
		this.author = author;
		this.isbn = isbn;
		this.isAvailable = isAvailable;
	}
	
	public String GetTitle() { return title; }
	public void setTitle(String title) { this.title = title; }
	public String getAuthor() { return author; }
	public void setAuthor(String author) { this.author = author; }
	public String getIsbn() { return isbn; }
	public void setIsbn(String isbn) { this.isbn = isbn; }
	public boolean isAvailable() { return isAvailable; }
	public void setAvailable(boolean available) { isAvailable = available; }

	public void displayDetails() {
		// TODO Auto-generated method stub
		
	}
}
