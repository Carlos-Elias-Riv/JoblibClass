# JoblibClass

#DockerFile
PARA MAC con m1: Dejar la primera línea como está: FROM --platform=linux/and64/amd64 python:3.9.1 as base
PARA EL RESTO: Cambiar la primera línea a lo siguiente: FROM python:latest as base

