# test-urls

urlfiltering.paloaltonetworks.com/test-malware

# test cc  

4111111111111111


# test malcode

def create_eicar_file(filename):
    eicar_string = r'X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*'
    # write as ASCII text
    with open(filename, 'w', encoding='ascii', newline='') as f:
        f.write(eicar_string)
    print(f"EICAR test file created: {filename}")

if __name__ == "__main__":
    create_eicar_file("eicar_test.txt")


