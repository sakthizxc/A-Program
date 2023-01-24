# A-Program

class Theater{
int total;
public static void main(String []args)
{
Theater raja=new Theater(200);
System.out.println("After booking I have");
raja.bookTicket();
}
Theater(int amount)
{
total=amount;
}
void bookTicket()
{
int Ticket_price=120;
int ballence=total-Ticket_price;
System.out.println(ballence+" "+"Ballence");
}
}
