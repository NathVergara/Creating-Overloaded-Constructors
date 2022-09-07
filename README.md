# Creating-Overloaded-Constructors
Creating Overloaded Constructors



public class CarInsurancePolicy
{
    public static void main(String[] args){
        int policyNumber = 205;
        int numberPayment = 509;
        String cityOfResidence = "Angeles";
        pol(policyNumber, numberPayment, cityOfResidence);
        pol(policyNumber, numberPayment);
        pol(policyNumber);
    }
    public static void pol(int policyNumber, int numberPayment, String cityOfResidence){
        System.out.println("Policy number: " + policyNumber);
        System.out.println("Number of Payments: "+ numberPayment);
        System.out.println("City of Residence: "+ cityOfResidence);
    }
    public static void pol(int policyNumber, int numberPayment){
        System.out.println("\nPolicy number: " + policyNumber);
        System.out.println("Number of Payments: "+ numberPayment);
    }
    public static void pol(int policyNumber){
        System.out.println("\nPolicy number: " + policyNumber);
    }

}



