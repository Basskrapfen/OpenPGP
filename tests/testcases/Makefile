# OpenPGP testcases Makefile
CXX?=g++
CXXFLAGS=-std=c++11 -Wall -c -pthread -I../gtest-1.7.0/include -I../..

debug: CXXFLAGS += -g
debug: all

all: test_aes128_ecb.o test_aes192_ecb.o test_aes256_ecb.o \
     test_blowfish_ecb.o test_camellia_ecb.o test_cast128_ecb.o test_idea_ecb.o \
     test_tripledes_ecb.o test_twofish_ecb.o \
     test_md5.o test_ripemd160.o test_sha1.o \
     test_sha224.o test_sha256.o test_sha384.o test_sha512.o \
     test_dsa.o test_rsa.o \
     test_compress.o test_pgp.o test_radix64.o

test_aes128_ecb.o:
	$(CXX) $(CXXFLAGS) test_aes128_ecb.cpp

test_aes192_ecb.o:
	$(CXX) $(CXXFLAGS) test_aes192_ecb.cpp

test_aes256_ecb.o:
	$(CXX) $(CXXFLAGS) test_aes256_ecb.cpp

test_blowfish_ecb.o:
	$(CXX) $(CXXFLAGS) test_blowfish_ecb.cpp

test_camellia_ecb.o:
	$(CXX) $(CXXFLAGS) test_camellia_ecb.cpp

test_cast128_ecb.o:
	$(CXX) $(CXXFLAGS) test_cast128_ecb.cpp

test_idea_ecb.o:
	$(CXX) $(CXXFLAGS) test_idea_ecb.cpp

test_tripledes_ecb.o:
	$(CXX) $(CXXFLAGS) test_tripledes_ecb.cpp

test_twofish_ecb.o:
	$(CXX) $(CXXFLAGS) test_twofish_ecb.cpp

test_md5.o:
	$(CXX) $(CXXFLAGS) test_md5.cpp

test_ripemd160.o:
	$(CXX) $(CXXFLAGS) test_ripemd160.cpp

test_sha1.o:
	$(CXX) $(CXXFLAGS) test_sha1.cpp

test_sha224.o:
	$(CXX) $(CXXFLAGS) test_sha224.cpp

test_sha256.o:
	$(CXX) $(CXXFLAGS) test_sha256.cpp

test_sha384.o:
	$(CXX) $(CXXFLAGS) test_sha384.cpp

test_sha512.o:
	$(CXX) $(CXXFLAGS) test_sha512.cpp

test_dsa.o:
	$(CXX) $(CXXFLAGS) test_dsa.cpp

test_rsa.o:
	$(CXX) $(CXXFLAGS) test_rsa.cpp

test_compress.o:
	$(CXX) $(CXXFLAGS) test_compress.cpp

test_pgp.o:
	$(CXX) $(CXXFLAGS) test_pgp.cpp

test_radix64.o:
	$(CXX) $(CXXFLAGS) test_radix64.cpp

clean:
	rm -f *.o

