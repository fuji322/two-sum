def twoSum(nums, target):
    for idx, val in enumerate(nums):
        for idx1, val1 in enumerate(nums):
            if (idx!=idx1) and (val+val1==target):
                return [idx,idx1]

a=twoSum(a,16021)
print a
