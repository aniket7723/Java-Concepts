# Java-Concepts

1) <img width="636" height="575" alt="image" src="https://github.com/user-attachments/assets/564ef452-c675-4261-86c0-842f59eb604a" />
public class Solution {
    public int solve(int A) {
        int count = 0;
        for(int i=1; i*i<=A; i++){
            if(A%i==0 && i == A/i){
                count++;
            }
            else if(A%i==0){
                count = count + 2;
            }
        }
        return count;
    }
}
