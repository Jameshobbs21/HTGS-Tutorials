add_executable(hadamard-product-no-read
        tutorial2-hadamard--no-read-main.cpp
        data/MatrixRequestData.h
        data/MatrixBlockData.h
        data/MatrixBlockMulData.h
        tasks/GenMatrixTask.h
        memory/MatrixMemoryRule.h
        memory/MatrixAllocator.h
        rules/MatrixLoadRule.h
        tasks/HadamardProductTask.h)