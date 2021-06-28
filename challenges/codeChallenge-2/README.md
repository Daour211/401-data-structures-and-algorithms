The soltuion for the second code challenge of insert Shift Array

![insert-Shift- Array-solution](../codeChallenge-2/codeChallenge2.jpg)

The code:

public static void main(String[] args){

int num = 5;
ArrayList< Integer> arr = new ArrayList< Integer>();<br>
insertShiftArray(arr , num);
}

public static void insertShiftArray(ArrayList< Integer> arr, int num){

arr.add(2);<br>
arr.add(4);<br>
arr.add(6);<br>
arr.add(-8);<br>
arr.add(10);

        int position = arr.size() / 2 ;
        System.out.println("position=" + position);
        arr.add(position,num);
        System.out.println(arr);

    }
