EXECS=mpi_hello_world
MPICC?=mpicc
BIN_DIR=bin

all: ${EXECS}

mpi_hello_world: mpi_hello_world.c
	${MPICC} -o ${BIN_DIR}/mpi_hello_world mpi_hello_world.c

clean:
	rm ${EXECS}