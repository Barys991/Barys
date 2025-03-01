# Barys
Crmp
#include <a_samp> // SAMP API-ін қосу

main() {
    print("CRMP сервері сәтті іске қосылды!");
}

// Ойыншы серверге қосылғанда шығатын хабарлама
public OnPlayerConnect(playerid) {
    SendClientMessage(playerid, 0x00FF00FF, "Сәлем! Серверге қош келдіңіз!");
    return 1;
}

