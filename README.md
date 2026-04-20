🚀 283. Move Zeroes

📌 Problem Statement

Given an integer array nums, move all 0s to the end of it while maintaining the relative order of the non-zero elements.

You must do this in-place without making a copy of the array.

🧠 Approach

First, find the index of the first zero.

Then iterate through the rest of the array.

Whenever a non-zero element is found, swap it with the zero pointer and move the pointer forward.

This ensures all non-zero elements are shifted forward while zeros move to the end.
