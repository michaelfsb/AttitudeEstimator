# CMakeList.txt: projeto de CMake para AttitudeEstimator, incluir origem e definir
# lógica específica a um projeto aqui.
#
cmake_minimum_required (VERSION 3.8)

project ("AttitudeEstimator")

# Adicione a origem ao executável deste projeto.
add_executable (AttitudeEstimator "AttitudeEstimator.cpp" "AttitudeEstimator.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET AttitudeEstimator PROPERTY CXX_STANDARD 20)
endif()

# TODO: Adicione testes e instale destinos, se necessário.
