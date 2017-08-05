# two-sum
leetcode 
/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int* twoSum(int* nums, int numsSize, int target) {
    int i,j,x=0;
    int a[10],int b[10];
    numsSize=sizeof(nums)/sizeof(sums[0]);
    for(i=0;i<numsSize;i++)
    {
        for(j=0;j<numsSize;j++)
        {
            if (nums[i]+nums[j]==target&&i!=j)
            {
                a[x]=i;b[x]=j;
                x++;
            }       
        }
    }
    
    for(x=0;i<10;i++)
    {
        if (a[x]!=0)
        {
            printf("'[' %d, ',' %d ']',&a[x],&b[x] ")
        }
    }
    
    return()
    
}
