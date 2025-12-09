def fibonachi():
    vector = [0, 1]

    for i in range(98):
        val = vector[i] + vector[i + 1]
        vector.append(val)

    return vector


def main():
    vector = fibonachi()   
    vector.reverse()       
    print(vector)



if __name__=="__main__":
    main()
