#pragma once
#include <stdio.h>
#include <iostream>

void DisplayBoard(char maze[10][16]);
void Move(char maze[10][16], int &x, int &y, bool &loop);
//void xpush(int a);
int xpop();
//void ypush(int a);
int ypop();
void push(int a, int b);
