FROM golang AS builder

WORKDIR /app

COPY ./main.go /app

RUN go build main.go

FROM golang:alpine AS runner 

WORKDIR /app

COPY --from=builder /app/main /app

ENTRYPOINT ["/app/main"]