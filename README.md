# ecommerce
public class BankAccount {
	private int id;
	private double value;
	
	public int getId() {
		return id;
	}
	public void setId(int id) {
		this.id = id;
	}
	public double getValue() {
		return value;
	}
	public void setInitialValue(double value) {
		this.value = value;
	}
	
	public void deposit(double v) {
		this.value += v;
	}
	
	public void withdraw (double v) {
		this.value -= v;
	}
}
