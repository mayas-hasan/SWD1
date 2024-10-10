//----------------------------------------------------------------------------------------------
// Name: Mayas Hassan Abu Alfaraj
// ID: 445006876
// This Java code performs a linear search for the element x in the array arr[]. 
// If x is present, it returns its location; otherwise, it returns -1.
class LinearSearch {

   
    static int search(int arr[], int n, int x) {
      
        for (int i = 0; i < n; i++) {
        
            if (arr[i] == x) {
                return i; // Element found at index i
            }
        }
      
        return -1;
    }

    public static void main(String[] args) {
       
        int[] arr = { 3, 4, 1, 7, 5 };
        int n = arr.length; // Length of the array
        int x = 5; // Element to search for (changed from 4 to 5)
        int index = search(arr, n, x); // Call the search function

        if (index == -1) {
            System.out.println("Element is not present in the array");
        } else {
            System.out.println("Element found at position " + index); // Output the index
        }
    }
}
//------------------------------------------------------------------------------------------------------
