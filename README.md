# car-project
{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 1,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "l=[10,20,30,40,50]\n",
    "k=l\n",
    "l is k\n",
    "l==k"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1978730277616"
      ]
     },
     "execution_count": 6,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a='$hello'\n",
    "b='$hello'\n",
    "id(a)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "140729875473392"
      ]
     },
     "execution_count": 21,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "a=10\n",
    "b=20\n",
    "id(b)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10\n",
      "20\n",
      "30\n",
      "40\n",
      "50\n",
      "60\n",
      "70\n"
     ]
    }
   ],
   "source": [
    "l=[10,20,30,40,50,60,70]\n",
    "for i in l:\n",
    "  print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0\n",
      "1\n",
      "2\n",
      "3\n",
      "4\n",
      "5\n",
      "6\n"
     ]
    }
   ],
   "source": [
    "for i in range(len(l)):\n",
    "    print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 27,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0\n",
      "1\n",
      "2\n",
      "3\n",
      "4\n"
     ]
    }
   ],
   "source": [
    "for i in range(5):\n",
    "    print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10\n",
      "20\n",
      "30\n",
      "40\n",
      "50\n",
      "60\n",
      "70\n"
     ]
    }
   ],
   "source": [
    "for i in range(len(l)):\n",
    "    print(l[i])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 35,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10   20   30   40   50   60   70   "
     ]
    }
   ],
   "source": [
    "for i in range(len(l)):\n",
    "    print(l[i],end='   ')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 36,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "enter any num:5\n",
      "5\n",
      "<class 'str'>\n"
     ]
    }
   ],
   "source": [
    "n=input('enter any num:')\n",
    "print(n)\n",
    "print(type(n))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 38,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "enter any num:5\n",
      "hello\n",
      "hello\n",
      "hello\n",
      "hello\n",
      "hello\n",
      "<class 'int'>\n"
     ]
    }
   ],
   "source": [
    "n=int(input('enter any num:'))\n",
    "for i in range(n):\n",
    "  print('hello')\n",
    "print(type(n))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "hello\n",
      "hello\n",
      "hello\n",
      "hello\n",
      "hello\n",
      "hello\n"
     ]
    }
   ],
   "source": [
    "i=0\n",
    "while i<=5:\n",
    "    print('hello')\n",
    "    i=i+1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 45,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2 2 2 2 2 \n",
      "3 3 3 3 3 \n",
      "4 4 4 4 4 \n",
      "5 5 5 5 5 \n"
     ]
    }
   ],
   "source": [
    "for i in range(4):\n",
    "    for j in range(5):\n",
    "        print(i+2,end=' ')\n",
    "    print()    "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
